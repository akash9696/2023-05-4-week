
## Areas
```dataview
table file.outlinks as Projects
from #area and -"notes/{ Databases/All Templates"
```



## Projects
```dataview
table file.inlinks as Area, file.outlinks as Task
from #project AND #doing 
```



## To Be Complete

```dataview
table L.text as Line
from ""
flatten file.lists as L
where contains(L.tags, "#tocomplete")
```

## Notes

```dataview
table file.etags
from #note   
```

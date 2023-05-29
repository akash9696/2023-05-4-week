
```dataview
table category as Tags, author as Author, ("![coverimg|90](" + Image + ")") as Illustration, Tags as Category
from #articles 
```


---

{% if image_url -%}
![rw-book-cover]({{image_url}})

{% endif -%}
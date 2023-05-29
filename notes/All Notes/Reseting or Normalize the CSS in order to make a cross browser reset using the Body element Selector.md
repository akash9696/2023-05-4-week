---
id: pv6r7r34xwxwhzzcfgf1th6
title: Reseting or Normalize the CSS in order to make a cross browser reset
  using the Body element Selector
desc: ""
updated: 1673111463314
created: 1673111463314
tag: css
---

---

```css
body {
  font-family: "Lato", sans-serif;
  font-weight: 400;
  font-size: 16px;
  line-height: 1.7;
  color: #777;
}
```

^26f6ff

---

1. Let's set some overall font properties for the entire webpage.
2. This time, we're not going to do it in the universal selector, but in the body element selector.
3. And why do we do it this way?
4. Well, we do it because the properties related to font are usually inherited, so we're using the power of inheritance here.
5. We have a whole lecture just about inheritance in CSS. What you need to know for now, is that we set, for example, the font family on the body element, which is basically the parent element of all the other elements.
6. Then this font family will get inherited to all the child elements of the body.
7. And doing it this way is actually more efficient, and it's a better practice than to just put all of this in the universal selector up there.
8. We never do that.
9. Everything related to font, we always specify it here in the body selector.
10. We set the font family to Lato.
11. And if that's not available, then just some Sans Serif.
12. I can use Lato because I already included it here in the html header.
13. This comes from Google fonts.
14. I included Lato with the font weights of 100, 300, 400, 700 and 900.
15. Let's set the overall font weight to just 400.
16. Also the overall font size should be 16 pixels and the line height of, let's say, 1.7.
17. So basically line height 1.7 means that it's 1.7 times bigger than the predefined line height, that we would have without this.
18. We're using 16 pixels here for now,
19. We can set here is the overall text color, which I'm sure you also know how to do it.
20. And then the color that I chose for this text is this gray, `777`
21. And with this code, we just performed a basic reset and we also set the project-wide font definitions here in the body selector because they will all be inherited to their child elements.

---

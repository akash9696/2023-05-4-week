---
id: 488ruiz6l4ou8itvzrcgolz
title: Reseting or Normalize the CSS in order to make a cross browser reset
  using the Universal Selector
desc: ""
updated: 1673111280802
created: 1673111280802
tag: css
---

---

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
```

^bd9cae

---

1. Above code will do a simple reset using the universal selector.
2. The universal selector will select each and every element on the page, and then apply these declarations here to it.
3. We want a `margin` on all of them of `0` pixels and of course also a `padding` of `0`.
4. By default, browsers apply a certain margin, or a certain padding, to some elements.
5. For example, an H1 element, there's always some margin in it.
6. And we don't want any of that.
7. This allows us basically to start clean, without the browser adding any `margins` or `paddings`, that we don't want, to our elements.
8. Another thing that we're gonna do, is to set a `box sizing` property to `border box`.
9. If you're not familiar with box sizing border box, what this does is to change the box model so that the borders and the paddings are no longer added to the total width or the total height that we specify for a box.
10. Without this, any paddings and borders are added to the height or the width of an element which really isn't helpful for us, and so with this, we're getting rid of that behavior.

---

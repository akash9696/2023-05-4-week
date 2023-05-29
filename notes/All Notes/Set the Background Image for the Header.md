---
id: 7lw97phj9ytelawpvwwkfne
title: Set the Background Image for the Header
desc: ""
updated: 1673189058095
created: 1673189058095
tag: css
---

---

```css
.header {
  height: 95vh;
  background-image: url(..img/hero.jpg);
  background-size: cover;
}
```

- Let's now set the background image.

I start typing background,

but instead of having to write all the way until background,

and then image, I can just start writing image right now,

because the text editor will recognize

that I'm looking for background image.

You see, it already recognized that that's what I want.

And this will also work in your text editor.

You can just do the same and you don't have to write

all the codes, like background image,

when instead just back img and then it works.

Press enter and that's it.

The background image that we want

is here in the image folder.

It is called hero, I think.

Yeah, so that's the one we want, right?

You see? It's this one here.

And we specify an image by writing url

and then specifying the path to the image.

Now we're currently in the CSS folder,

so we first have to go one folder up

to go into the project folder.

And so it's ../ then, img, so image,

and then the name of the image, hero.jpg

And that's it.

So again, we were here in the CSS folder

and we went one level up to go into the project folder

so the Natours folder here,

and then from there we went into the image folder,

and then hero.jpg.

And now something else we should do

is to set the background size to cover,

which I'm sure you're also familiar with.

Again, I do this trick.

I just write back, then I start writing size,

return, and that's it.

And cover is what I want here.

And what cover does is that whatever the width of

the viewport, or the element, it'll always try to fit

the element inside of the box.

Let's now take a look on what that looks like.

This one is it. Refresh. And here we go.

So our background image adapts nicely to the viewport,

I hope.

And yeah, it does.

And you see here this white bar,

it's the remaining 5% of the viewport height.

100% would fill everything.

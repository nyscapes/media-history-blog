---
title: Markdown Cheat Sheet
author: mds17 
redirect_from: /2018/01/31/markdown-cheat-sheet.html
permalink: /markdown-cheat-sheet
layout: post
date: 2018-01-31
---

You should write your blog posts in Markdown and get in the habit of using it.
Here are some of the most commonly used ways to write things:

## Text formatting

```
If I want to write in _italics_, I surround it by underscores.

For **bold**, I use **2** asterisks.
```

creates: 

If I want to write in _italics_, I surround it by underscores.

For **bold**, I use **2** asterisks.

## Links

There are three kinds of links: to webpages, to images on the internet, and to
footnotes on the page.

### Linking to webpages

```
Writing some text in honor of [NYU](http://nyu.edu).
```

creates:

Writing some text in honor of [NYU](http://nyu.edu).

As you can see, the “NYU” part makes up the _text_ of the link, in “[]”
brackets, and the parentheses is where you put the url.

### Linking to images

The syntax is identical, except you add an exclamation point:

```
![Bobst Library](https://i.imgur.com/YRWsb6k.jpg)
```

creates:

![Bobst Library](https://i.imgur.com/YRWsb6k.jpg)

Here, “Bobst Library” appears as text to describe the image for people who
have impaired vision. Note that the image has to have a URL. I recommend
uploading images to [imgur.com](http://imgur.com) and then using those urls
for images.

### Linking to footnotes

Footnotes are a bit trickier, since while you’re writing, you can add a quick
marker to a footnote, but you have to define the footnote elsewhere:

```
This is some text I am writing about a footnote[^footnote-about-footnotes]

[^footnote-about-footnotes]: This is the text of the footnote.
```

creates:

This is some text I am writing about a footnote[^footnote-about-footnotes]

[^footnote-about-footnotes]: This is the text of the footnote.

Scroll down to the bottom of the page to see the footnote. You can call the
footnotes whatever you want, but that name has to be in “[]” brackets, can’t
have spaces, and has to begin with a “^” caret.

## Headers

```
# This is a header

## This is a subheader

###### This is six levels down
```

creates:

# This is a header

## This is a subheader

###### This is six levels down

## Blockquotes

```
> A blockquote begins with a “>” symbol and continues until a blank line. For
multiple paragraph blockquotes, keep adding “>” symbols.
```

creates:

> A blockquote begins with a “>” symbol and continues until a blank line. For
multiple paragraph blockquotes, keep adding “>” symbols.

## Lists

Finally, lists. Much like how blockquotes begin with a “>”, lists begin with
either a “*” or a “1.” depending on whether you want an unordered or ordered
list.

```
* This
* is
* an
* unordered list
```

creates:

* This
* is
* an
* unordered list

```
1. This
4. is
5. an ordered
1. list. Notice
100. that the numbers
2. don’t matter
```

creates:

1. This
4. is
5. an ordered
1. list. Notice
100. that the numbers
2. don’t matter

There’s a whole lot more that Markdown can do, but this should cover most of
your bases for this course.

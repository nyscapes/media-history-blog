---
title: Adding Images, Video, and Sound to Your Posts
author: mds17
redirect_from: /2018/02/10/adding-images-video-sound.html
permalink: /adding-images-video-and-sound
layout: post
---

Markdown deals with text. But we want our posts to be multimodal. How to add
pictures, video, and sound? All of these feature a two step process:

1. Put the picture, video clip, or sound recording on the internet.
1. Embed a link to that picture, clip, or recording in your post.

For videos and sound, I recommend using [YouTube](http://youtube.com) or
[SoundCloud](http://soundcloud.com). For images, I recommend using
[Imgur](http://imgur.com)

Here is a video that shows the process for all three:

<div class="embed-responsive embed-responsive-21by9">
<iframe width="560" height="315" src="https://www.youtube.com/embed/2ivKEj3ksPk" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>

## Images

Uploading the images to Imgur is straightforward: you click on “New post” and
drag the image you want to upload onto the webpage, and that’s about it. Once
the image is on the internet, however, you need to get the address for the
image itself.

Get the address by hovering your mouse in the top-right corner of the image
and clicking on the dropdown menu. Pick “Get share links” and then copy the
one for “BBCode.”

In your post, use the Markdown syntax for your image:

`![Bobst](https://i.imgur.com/4LdtsQs.jpg)`

The text you copy from Imgur will also have `[img]` and `[/img]` tags in it,
which you’ll have to delete.

## Video and Sound

Embedding YouTube and SoundCloud clips is the same process: you click on
“Share” and then “Embed,” to get a long `<iframe>` bit of HTML code.

Paste that code straight into your post.

For YouTube videos one extra step is needed, namely surrounding the `<iframe>`
code with some `<div>` code, like this:

```
<div class="embed-responsive embed-responsive-21by9">
<iframe width="560" height="315" src="https://www.youtube.com/embed/2ivKEj3ksPk" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>
```

The top line and bottom line are added by you.

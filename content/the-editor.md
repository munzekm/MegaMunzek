---
title: Resume
image: /images/writing.jpg
imageMeta:
  attribution:
  attributionLink:
featured: true
authors:
  - ghost
date: Tue Jun 12 2018 17:58:54 GMT+0100 (IST)
tags:
  - getting-started
---

empress-blog uses a language called **Markdown** to format text, and so does the original Ghost 🎉

The main difference between the hosted Ghost platform and empress-blog is that we just use files on disk, so you can either edit your Markdown files directly or you can use a desktop Markdown editor. It keeps things simple but it can sometimes feel like you are writing on pro-mode 😎

If you want to start a new post we recommend that you use the built in generator `ember generate post "The next big thing - empress-blog"`. This will create a file for you and setup the start of the metadata.

For now, though, let's run you through some of the basics of editing Markdown. You can see this post [directly on github](https://github.com/empress/empress-blog/blob/master/blueprints/empress-blog/files/__base__/content/the-editor.md) if you want to see all the Markdown we've used. (don't forget to click the _Raw_ button to see the source).


## Formatting text

The most common shortcuts are of course, **bold** text, _italic_ text, and [hyperlinks](https://example.com). These generally make up the bulk of any document. You can also make headings using `#` at the start of the line (multiple `#` symbols for h2/h3/h4/etc)

With just a couple of extra characters here and there, you're well on your way to creating a beautifully formatted story.


## Inserting images

Images in Markdown look just the same as links, except they're prefixed with an exclamation mark, like this:

`![Image description](/path/to/image.jpg)`

![Computer](https://casper.ghost.org/v1.0.0/images/computer.jpg)

If you want to add images to your empress-blog app you can just drop them in the `/public` folder, which you should see if you are running this locally!

_**Important Note:** empress-blog does not currently have automatic image resizing, so it's always a good idea to make sure your images aren't gigantic files **before** adding them to your project._

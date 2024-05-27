---
layout: post
title: "Blogging with style"
subtitle: 'About the small decisions with most impact'
header-style: text
tags:
  - Blog
  - Web
  - Design
---

Following up on my last post I now want to go a little more into the detail of the styling I chose for the blog. By briefly presenting all the different elements here I'd like to tell you a bit about my reasoning and will also use this as a reference page for later adjustments.

Let's start with...

## Fonts

Probably the most fundamental choice for a website that's all about text and therefore not that easy. Especially in light of the myriads of options available out there in the wide web. So I had to narrow it down heavily first to come to any decision at all.

Its license should be free to use for my purpose. And it should work great in web context. [Google Fonts](https://fonts.google.com/) are the obvious choice for that. A large collection of free and open source fonts Google hosts on its servers to be downloaded or used directly on a webpage. That brings us down from myriads to only 1639 font families (at the time of this post).

Most important of all is the default font used throughout all text that requires no special emphasis. The kind of text you will read mostly and you're reading right now. I wanted it to be without serifs - to be more web and less print like - and have at least four styles - hopefully including regular, bold, italic and bold italic. That leaves us with 367 fonts still. So the rest was up to me scrolling through the remaining list down from the most popular fonts.

And I stopped at [Nunito](https://fonts.google.com/specimen/Nunito). Because its rounded edges make the most pleasing and least harsh impression. I don't want my blog to be like a scientific paper, but a nice chat over niche interests. And that's one way to convey it.

Accordingly, I wanted the style for code snippets and the top-most headline here to be rounded as well. But these elements also have some special requirements I needed different fonts for. The headline should look striking on its own, with serifs to add interesting details to each letter. So I chose [Alegreya](https://fonts.google.com/specimen/Alegreya). And because blocks of code rely on consistent indentation for structure, it's best to use a monospaced font for them. Meaning that each character (letter, number, symbol or space) has the same width and all lines starting with two spaces for instance align perfectly. This made me use [Ubuntu Mono](https://fonts.google.com/specimen/Ubuntu+Mono) there.

## Inserts

And while we're talking about code snippets why not show you one example here:

```typescript
export interface IScene extends DisplayObject {
  input: (position: Point, button?: string) => void;
  update: (framesPassed: number) => void;
}
```

You see the text alignment guaranteed by the monospaced font? Nice, isn't it? :grinning:

At least for someone reading a lot of it each day. But the other thing I wanted to show you here is the way I chose other elements in-between paragraphs to be framed. Subtle but distinct, looking like a portion of the page was cut out to let the insertion shine through. All done with a simple shadow effect and different background color for the code section. The same goes for images like the one below:

![img](/blog/img/bg-about.jpg)

## Quotes

> "Good design is as little design as possible." (Dieter Rams[^drams])

And about the styling of quotes I thought to pay heed to this one here and do nothing more than necessary. It needs to differ clearly from the rest of the text to emphasize it's not my own. So I made it italic, faded and indent a bit - in addition to the standard quotation marks and author of course. But that should be it. Because when I annotate my own thoughts to some more cited lines in the future, I want you to be able to read it over without too much stumbling.

But for now you read enough of my lines already to end it here. I'll leave you be with the rest of a delightful day and hope this post could add something to it. :blush:

<br>

---
[^drams]: German industrial designer with big influence on design practices and aesthetics of the 20th century. ([Wikipedia link](https://en.wikipedia.org/wiki/Dieter_Rams))

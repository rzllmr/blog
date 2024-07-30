---
layout: post
title: "A little RPG for your pocket"
subtitle: "Early concepts for a long project"
header-style: text
tags:
  - Video Game
---

Hi! :wave: I recently worked on a game again. One I'll probably keep developing for a long time and maybe never even finish. But I have a lot of fun in the process and can share some interesting thoughts already. So I hope you bear with me to see...

## What it should be

When I set out to make a new game, it is as with all my creative projects: I see myself confronted with a blank page. Everything is imaginable. That's why we want to limit it quickly here now, before being overwhelmed by the possibilities. Let's start right away...

I want to make an RPG of any kind.
: Phew, that's a BIG ambition already. But ok, maybe that "any kind" got enough leverage to scale it down to something achievable. I just really want to create little worlds to tell short stories in - through gameplay and not just text. It doesn't need to be like any of those fully blown RPGs you know. I want to start <u>very</u> small, make the best of the features I have and build upon it with each new episode.
<br><br>

I want to do most of it myself.
: Another point to extend the development time to forever. But that aspect's really the most fun to me, to be able to tinker with everything I want. Writing the game engine myself for example, with only a few parts I gladly hand to existing libraries. And by using web technologies I believe to greatly accelerate the workflow. Why, I'll explain another time.
<br><br>

I like it to have low resolution 2D pixel art aesthetics.
: Because that's a good constraint to trim the efforts down a bunch. It means simpler assets for a simple renderer[^renderer] I chose to be [PixiJS](https://pixijs.com/). To outright relieve me of that kind of work. And the style I also dig a lot. Although some people might be fed up with it being over-present among indie games, I still think it effectively serves to a level of abstraction that leaves neat gaps to your imagination. While being pretty adorable. :blush:
<br><br>

It shall play great on mobile.
: What that really means for the design I will find out - possibly the hard way. But the idea to have the game playable by almost everyone out there without any technical hurdles is wondrous. And at first glance I would even think it's a helpful limitation. To keep the focus on few elements, less clutter and intuitive handling. To throw everything out that's not in service of the intended experience. What could be especially important for this ever growing project.

## What it is right now

All right, all right, all those fine words aside about what I wish for, let's get to the real thing. The technological base is established - taking me much longer than this brief sentence conveys. It allows me to deploy the game to [itch.io](https://itch.io/) now, where anyone could launch it in the browser on their phone, and play around with just a little. Looking like this in a side-by-side view of two different states:

![img](/blog/img/in-post/screenshot-dare_130.png)

If you want to try it yourself, just follow this [link](https://rzllmr.itch.io/dare). But as of now it is nothing more than a technical prototype without much content. This will change, though, and I'll keep you posted about every milestone here in this blog.

See you then! :wink:

<br>

---
Game art assets: Largely inspired by or directly adapted from [Pocket Inventory Series #7: Gems of Status](https://humblepixel.itch.io/pocket-inventory-series-7-gems-of-status) by [Humble Pixel](https://humblepixel.itch.io/) bought on [itch.io](https://itch.io/) under [individual license](https://humblepixel.itch.io/pocket-inventory-series-7-gems-of-status)<br>
Book font: CelticTime from [Nb Pixel Font Bundle](https://nimblebeastscollective.itch.io/nb-pixel-font-bundle) by [Nimble Beasts Collective](https://nimblebeastscollective.itch.io/) on [itch.io](https://itch.io/) under [CC0](https://creativecommons.org/public-domain/cc0/)

[^renderer]: The renderer is the part of a game engine responsible for drawing the graphical elements on the screen. ([Wikipedia link](https://en.wikipedia.org/wiki/Rendering_(computer_graphics)))

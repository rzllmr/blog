---
layout: post
title: "How I set up this blog"
subtitle: 'And how you could do it, too'
header-style: text
tags:
  - Blog
  - Web
  - Coding
---

Obviously the first thing I was busy with lately was setting up this blog. So, why not talk about how it came to be in the first post?

The basis for it is a [Jekyll](https://jekyllrb.com/) powered website written in [Markdown](https://www.markdownguide.org/) hosted on [GitHub](https://pages.github.com/) with the styling of [Hux Blog](https://huangxuan.me/). But let's unravel that a bit.

### Jekyll

What would you say if you could just write some simple text files to fill your own website with? If it's "Meh" than this post maybe isn't the right one for you but I think that's awesome. Posting something like you're reading right now is nothing more than putting the text down as you see below and doing some clicks to publish it.

```markdown
### Jekyll
What would you say if you could just write some simple text files to fill your own website with? If it's "Meh" than this post maybe isn't the right one for you, but I think that's awesome. Posting something like you're reading right now is nothing more than putting the text down like below and doing some clicks to publish it.
```

And that's because [Jekyll](https://jekyllrb.com/) is doing the heavy lifting of transforming those text files into actual HTML to be displayed as a webpage. You configure it, run it and put the results on a server. Maybe I do another post about the details of that, but for now I will just point you to the README of my repository[^repo] that houses everything needed for this blog here: [https://github.com/rzllmr/blog](https://github.com/rzllmr/blog).

### GitHub Pages

In fact you don't really need to know everything of the technical details to have your own blog set up the same way as mine. That's the power of open source hubs like [GitHub.com](https://github.com/). You can just create an account, *copy* my repository, *download* it to your computer, *make the changes* - like throwing my stuff out and yours in - and *upload* that again to be published automagically. The words for those actions in the [git](https://git-scm.com/) program that's used by Github are *fork*, *clone*, *commit* and *push*. And I must admit those concepts are a bit difficult to grasp at first, so you probably won't get around watching some tutorials about it, sorry...

BUT (notice the capital "but" here) when you're able to perform the steps above you can just write a blog post in a text file, upload it to GitHub and wait for it to publish it to your website. Easy peasy... After a considerable amount of effort for the setup. :sweat_smile:

### Hux Blog

I myself forked[^fork] the [repository](https://github.com/Huxpro/huxpro.github.io) of [Hux Blog](https://huangxuan.me/) from Huang, Xuan to create my own blog here. The general style and feature set he used, itself based on the [Clean Blog Jekyll](https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll) theme, spoke to me visually and practically. So I started from that and adapted it to my liking in facets big and small. And will probably do so again every once in a while. But I think that should be something for another follow up post. This one is long enough as it is. And I already spend too much time writing it.

So, see you next time! :wink:

<br>

---
[^repo]: A repository is a directory tree containing all sorts of files and their history. ([GitHub Docs link](https://docs.github.com/en/repositories/creating-and-managing-repositories/about-repositories))
[^fork]: Forking means copying the complete state of a repository at a certain time to your own space to work on it alongside. ([GitHub Docs link](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo))

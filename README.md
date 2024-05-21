# [Rob's Blog](https://rzllmr.github.io/blog/)
> My place to publish everything fun that keeps me busy.

This is the source of everything you see on my [blog page](https://rzllmr.github.io/blog/). So for the technologically interested you find a description of the directory structure and processes set up here to style the blog and write new content for it. All with the central idea that posting new entries then requires nothing more than adding a markdown file to a folder.

The technologies used to accomplish that are as follows:
- **Ruby** with **bundler** to obtain the Jekyll gem
  - **Jekyll** to generate html pages from templates and markdown
    - using **Liquid** to write the templates
- **Node.js** with **npm** to run Jekyll, Grunt and a local server
  - **Grunt** to compile less to css and minify js files
- **GitHub** to host the files and build and serve the website

## Getting Started

1. [Fork](https://github.com/rzllmr/blog/fork) and clone this repository.
1. Install [Ruby](https://www.ruby-lang.org/en/) usually coming with [bundler](https://rubygems.org/gems/bundler) gem.
1. Run `bundle install` in the checkout's root directory to install Ruby gems listed in [Gemfile](./Gemfile) including [Jekyll](https://jekyllrb.com/).
1. Run `npm install` there as well to install JavaScript dependencies listed in [package.json](./package.json) including [Grunt](https://www.npmjs.com/package/grunt).
1. Run `npm start` to let Jekyll build and serve the blog page locally.
1. ...or `npm run dev` to make Grunt also update everything after any change to the source files.

## File structure

- **.github/workflows/jekyll.yml**: configuration of the GitHub action to generate the website
- **_includes/**: template html files for parts of the page
- **_layouts/**: template html files for the different general page layouts
- **_posts/**: markdown files for each post
  - **yyyy-mm-dd-name.md**: file name format with date and title
- *_site/*: generated files to serve as static website
- *css/*: stylesheets generated from less files
- **fa-icons/**: font-awesome icons to be used on the website
- **fonts/**: fonts used on the website
- **img/**: image files used on the website
- **js/**: JavaScript files used on the website
- **less/**: less files defining website's styling
- **pwa/**: icons and manifest for progressive web app
- **\*.html**: major pages besides posts
- **_config.yml**: configuration of Jekyll
- **CNAME**: canonical name of the website
- **feed.xml**: configuration of rss feed
- **Gemfile**: configuration of bundler
- **Gruntfile.js**: configuration of Grunt
- **LICENSE**: license file of original repository
- **NOTICE**: list of modified files under license
- **package.json**: configuration of npm actions
- **Rakefile**: script to create new post file
- **search.json**: configuration of search feature
- **sw.js**: configuration of service worker

## Additional resources

- README of the original repository: https://github.com/Huxpro/huxpro.github.io
- User manual for Hux Blog: https://github.com/Huxpro/huxpro.github.io/blob/master/_doc/Manual.md

- Liquid template engine: https://github.com/Shopify/liquid
- Less language features: https://lesscss.org/features/
- Jekyll variables: https://jekyllrb.com/docs/variables/

## License

Blog content by me<br>
Copyright (c) 2024-present rzllmr

Apache License 2.0<br>
Copyright (c) 2015-present Huxpro

Hux Blog is derived from [Clean Blog Jekyll Theme (MIT License)](https://github.com/BlackrockDigital/startbootstrap-clean-blog-jekyll/)<br>
Copyright (c) 2013-2016 Blackrock Digital LLC.

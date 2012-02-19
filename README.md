Static Prototyping Framework
============================

A template for rapid prototyping of static sites and applications. It's built on Jekyll and uses the HTML5 Boilerplate index.html and file structure, a modified subset of Twitter's Bootstrap CSS, and Sass with Bourbon mixins.

Jekyll
------
[Jekyll](https://github.com/mojombo/jekyll) is a blog-aware, static site generator. However, I've include it here for the purpose of writing HTML in a DRY manner. Using Jekyll allows you to use includes so you don't have to maintain multiple instances of the same code blocks. Unlike using PHP includes, Jekyll will output a directory of compiled static HTML files with your include code moved into each page. Using Jekyll also starts a web server on your computer, so you can easily use things like TypeKit that are normally a pain to work with in a local static site.

To use Jekyll, you'll need to [install the gem](https://github.com/mojombo/jekyll/wiki/install) from your Terminal.

For more information on using Jekyll, read [the guide](https://github.com/mojombo/jekyll/wiki/usage).

HTML
----
This project's HTML is based on the best practices advocated by the [HTML5 Boilerplate](http://html5boilerplate.com/) project.

The [Modernizr.js](http://www.modernizr.com/) library is included to support HTML5 elements and feature detection. I've included the default build from HTML5 Boilerplate, but you should probably [build your own custom version](http://www.modernizr.com/download/) to use only the features you want to support.

CSS
---
I've included a stripped-down version of [Bootstrap] (http://twitter.github.com/bootstrap/), Twitter's CSS toolkit. By default Bootstrap is built to work with LESS, but I've modified my version to work with [Sass](http://sass-lang.com/). The modified stylesheets I've included are:

* Variables
* Mixins
* Reset
* Type
* Forms
* Tables
* Buttons

These files represent what I would consider the basic default styles for most projects. If you prefer LESS or want more defaults, just remove the /stylesheets/sass directory and replace it with Bootstrap's /less directory. This project does not intend to support LESS usage, so if you go that route you're on your own.

###Bourbon
[Bourbon](https://github.com/thoughtbot/bourbon) by thoughtbot is included to allow the rapid use of CSS3 properties plus some other nice extras.

Artwork directory
-----------------

I've included empty PSDs with the proper names and sizes for creating all the right Apple touch icons and a favicon. Read [this article](http://mathiasbynens.be/notes/touch-icons) for more info.

Working with this repo
----------------------

To use Sass and require Bourbon, you have to watch your .scss files from the Terminal and compile their output into the application.css file in the /stylesheets directory. To do so, use the Terminal to cd into the root directory of this repo, then run this command:

<code>sass --watch stylesheets/sass:stylesheets -r ./stylesheets/sass/bourbon/lib/bourbon.rb</code>

Start the Jekyll server by running this command in Terminal from the root directory of this repo:

<code>jekyll --server --auto</code>

You can view your running application at [http://localhost:4000](http://localhost:4000).

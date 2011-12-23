Static Site Starter
===================

Template for starting static sites including Sass, Bourbon and Twitter Bootstrap

HTML5 Boilerplate
-----------------
Includes some [HTML5 Boilerplate](http://html5boilerplate.com/) goodness in the index.html file, plus the [Modernizr.js](http://www.modernizr.com/) library.

Items were added from version 2.0, which was originally authored on August 10th, 2011.

I took these items from the site on December 18, 2011.

Sass
----
Better CSS. For more, see [the Sass homepage](http://sass-lang.com/).

Bourbon
-------
thoughbot's set of [Sass mixins](https://github.com/thoughtbot/bourbon).

Twitter Bootstrap
------
Base CSS toolkit: http://twitter.github.com/bootstrap/

Jekyll
------
The file structure is set up to use Jekyll. To use it, [install the gem](https://github.com/mojombo/jekyll/wiki/install).
For more on Jekyll, read [the guide](https://github.com/mojombo/jekyll/wiki/usage).

Using Sass/Bourbon and Jekyll
-------------------------
Watch Sass stylesheet and require Bourbon. This will also pull Twitter Bootstrap styles into your main stylesheet:

    sass --watch stylesheets/sass:stylesheets -r ./stylesheets/sass/bourbon/lib/bourbon.rb

Start the Jekyll server:

    jekyll --server --auto

You can view your running application at [http://localhost:4000](http://localhost:4000).

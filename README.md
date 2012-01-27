Static Prototyping Framework
===================

A template for rapid prototyping of static sites and applications. It's built on Jekyll and includes parts of HTML5 Boilerplate, Bootstrap CSS and JS, plus Sass and Bourbon to facilitate easy and rapid development. This is not intended to be used for production sites in its default format. It pulls in a LOT of CSS and JS. If you wish to use it for production sites, you should delete unused styles and javascript and erase any comments that seem obvious to you.

HTML5 Boilerplate
-----------------
Includes some [HTML5 Boilerplate](http://html5boilerplate.com/) goodness in the default.html layout file, plus the [Modernizr.js](http://www.modernizr.com/) library. I erased a lot of the comments from the index file, you should refer to HTML5 Boilerplates documentation is you're not sure what something is.

Twitter Bootstrap CSS
------
Includes [Bootstrap] (http://twitter.github.com/bootstrap/), Twitter's CSS toolkit.

Twitter Bootstrap JS libraries
------
Includes the [Bootstrap JS libraries] (http://twitter.github.com/bootstrap/javascript.html) in javascripts/plugins.js to extend functionality.

Sass
----
Sass is better CSS and is include to simplify rapid front-end development. For more, see [the Sass homepage](http://sass-lang.com/).

Bourbon
-------
Bourbon is thoughbot's set of Sass mixins, intended to make the use of CSS3 properties faster. For more, see [Bourbon's GitHub repo](https://github.com/thoughtbot/bourbon).

Jekyll
------
The file structure is set up to use Jekyll. To use it, [install the gem](https://github.com/mojombo/jekyll/wiki/install).
For more on Jekyll, read [the guide](https://github.com/mojombo/jekyll/wiki/usage).

Using Sass/Bourbon and Jekyll
-------------------------
Watch Sass stylesheet and require Bourbon:

    sass --watch stylesheets/sass:stylesheets -r ./stylesheets/sass/bourbon/lib/bourbon.rb

Start the Jekyll server:

    jekyll --server --auto

You can view your running application at [http://localhost:4000](http://localhost:4000).

Consider setting up some aliases for these commands. If you always use the same file structure it will make life much easier. I use sassw to watch Sass, sasswb to watch Sass and include Bourbon, and jeks to start the Jekyll server.

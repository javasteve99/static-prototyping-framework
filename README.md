Static Prototyping Framework
===================

A template for rapid prototyping of static sites and applications. It's built on Jekyll and uses the HTML5 Boilerplate index.html and file structure, and Bootstrap CSS and JS. It pulls in a LOT of CSS and JS by default. If you wish to use it for production sites, you should delete unused styles and javascript.

HTML5 Boilerplate
-----------------
Includes some [HTML5 Boilerplate](http://html5boilerplate.com/) goodness in the default.html layout file, plus the [Modernizr.js](http://www.modernizr.com/) library. I erased a lot of the comments from the index file, you should refer to HTML5 Boilerplate's documentation if you're not sure what something is. I also combined the HTML5 Boilerplate file structure with the Jekyll file structure.

Twitter Bootstrap CSS
------
Includes a stripped down and modified for Sass version of [Bootstrap] (http://twitter.github.com/bootstrap/), Twitter's CSS toolkit. Default styles for rapid development.

Sass and Bourbon
----------------
Sass is a dynamic stylesheet language that makes writing CSS easier and faster. For more, see [the Sass homepage](http://sass-lang.com/).

Bourbon is a set of Sass mixins that makes writing CSS3 properties as simple as possible. For more, see it's GitHub repo.

To use Sass and Bourbon, you have to watch them from the Terminal and compile their output into the application.css file in the /stylesheets directory. To do so, use the Terminal to cd into the root directory of this repo, then run this command:

sass --watch stylesheets/sass:stylesheets -r ./stylesheets/sass/bourbon/lib/bourbon.rb

Jekyll
------
The file structure is set up to use Jekyll. To use it, [install the gem](https://github.com/mojombo/jekyll/wiki/install).
For more on Jekyll, read [the guide](https://github.com/mojombo/jekyll/wiki/usage).

Start the Jekyll server by running this command in Terminal from the root directory of this repo:

jekyll --server --auto

You can view your running application at [http://localhost:4000](http://localhost:4000).

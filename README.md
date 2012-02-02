Static Prototyping Framework
===================

A template for rapid prototyping of static sites and applications. It's built on Jekyll and uses the HTML5 Boilerplate index.html and file structure, and Bootstrap CSS and JS. It pulls in a LOT of CSS and JS by default. If you wish to use it for production sites, you should delete unused styles and javascript.

HTML5 Boilerplate
-----------------
Includes some [HTML5 Boilerplate](http://html5boilerplate.com/) goodness in the default.html layout file, plus the [Modernizr.js](http://www.modernizr.com/) library. I erased a lot of the comments from the index file, you should refer to HTML5 Boilerplates documentation is you're not sure what something is. I also combined the HTML5 Boilerplate file structure with the Jekyll file structure.

Twitter Bootstrap CSS
------
Includes [Bootstrap] (http://twitter.github.com/bootstrap/), Twitter's CSS toolkit. Default styles for rapid development, and LESS mixins for rapid use of CSS3 and other properties.

Twitter Bootstrap JS libraries
------
Includes the [Bootstrap JS libraries] (http://twitter.github.com/bootstrap/javascript.html) in javascripts/plugins.js to extend functionality.

LESS
----
LESS is a dynamic stylesheet language that makes better CSS. For more, see [the LESS homepage](http://lesscss.org/).

Rather than use the JS file to compile .less files on the server, I set this up to take advantage of compiling locally into a single .css file. To do so, I recommend the unofficial Mac [LESS](http://incident57.com/less/) app.

Once the app is installed, drag the root folder onto the app interface to start watching .less files in your project. Then, right-click on the application.less file and set the app to compile it's output to the application.css file one level up. You only need to do this once, as long as the LESS app is open it will recompile whenever you save.

You could also do this from the command line by following the documentation, but the app makes life much easier.

Jekyll
------
The file structure is set up to use Jekyll. To use it, [install the gem](https://github.com/mojombo/jekyll/wiki/install).
For more on Jekyll, read [the guide](https://github.com/mojombo/jekyll/wiki/usage).

Start the Jekyll server by running this command: 

jekyll --server --auto

You can view your running application at [http://localhost:4000](http://localhost:4000).

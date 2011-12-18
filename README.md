Static Site Starter
===================

Template for starting static sites including Sass, Bourbon and Flutie

HTML5 Boilerplate
-----------------
Includes some HTML5 Boilerplate goodness in the index.html file, plus Modernizr.js library - http://html5boilerplate.com/ 
Items were added from version 2.0, which was originally authored on August 10th, 2011.
I took these items from the site on December 18, 2011.

Sass
----
Better CSS: http://sass-lang.com/

Bourbon
-------
thoughbot's set of Sass mixins: https://github.com/thoughtbot/bourbon

Flutie
------
Default styles for your site/application: https://github.com/thoughtbot/flutie

Jekyll
------
The file structure is set up to use Jekyll, but you need to install the gem to use it properly: https://github.com/mojombo/jekyll/wiki/install
Here's how to use Jekyll: https://github.com/mojombo/jekyll/wiki/usage

Using Sass/Bourbon/Flutie and Jekyll
-------------------------
Watch Sass stylesheet and require Bourbon. This will also pull Flutie styles into your main stylesheet:
sass --watch stylesheets/sass:stylesheets -r ./stylesheets/sass/bourbon/lib/bourbon.rb

Start the Jekyll server: jekyll --server --auto
You can view your running application at http://localhost:4000

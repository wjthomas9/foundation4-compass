Foundation 4 Project with Compass Framework
===================

Project starter repo for a new Foundation 4 project using the Compass framework. Great for getting started quickly with html prototyping.

This repo uses *Bundler* to manage gems, and *Guard* to run command-line processes to minify and concatenate CSS and Javascript. 

You will also need to install juicer and your choice of compressor. (YUI compressor, Closure Compiler, or JsMin). You will only need to do the juicer installation once. Visit the juicer repo on github for more instructions on installation. https://github.com/cjohansen/juicer

To use
-------------------
1. clone repo
2. cd to site/assets/
3. run bundle install to get the necessary gems
4. run bundle exec guard to start the Guard processes

Once you do the above steps, Guard will be running and you can start workign with Sass, JS, and your html templates.

There is a directory called "static" where I typically create my html templates while I'm prototyping. If you change this directory, or it's location, be sure to update the watch location in the Guardfile for your html templates.
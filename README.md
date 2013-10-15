Slides for Gradle 2013 tech talk
=======

Presentation here: http://payne.github.io/Gradle2013Slides

#### Thanks to Jeff Sheets!
* Jeff used a wonderful setup for his slides in his talk
  * https://github.com/jeffsheets/JavaTesting2013Slides
* I have forked his repo and filled it with some info on Gradle

#### Dependencies
* Node
* Bower

####Getting Started
* Run `npm install` to install node dependencies
* Run `bower install` to install client-side dependencies

####Grunt Commands
* `grunt assemble`
  * Minify/uglify the javascript source and css
  * Compiles jade
  * Stages everything in the dist folder
* `grunt run`
  * Starts a server running on port 8000
  * watches for changes on project files
  * When files change, the assemble task is re-run and
  * Livereload triggers browser update on assemble task completion
* `grunt publish`
  * Publishes slides to GitHub pages
  * Uses git subtree merge to merge the contents of dist into the gh-pages branch

  Thanks to Mike Kelly for the reveal.js template! https://github.com/mrkelly/reveal-template


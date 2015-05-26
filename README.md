# Draw2D JS boilderplate project

Preview: http://freegroup.github.io/draw2d_js.app.starterkit_simple/

Demo project to build a basic HTML5 diagramming application with the http://www.draw2d.org
framework.

You need bower and grunt to build the Draw2D demo app.

Grunt runs on Node.js, so if you don't have npm installed already, go ahead and install it.

##To install Grunt's command line interface run:

```
npm install -g grunt-cli
```

With the flag -g you installed it globally and now you can access it from anywhere on your system.

##Bower
Installing bower couldn't be simpler. Just go:
```
npm install -g bower
```
and you have it.

##Download draw2d.js
and all required libraries in the right version with one command
```
bower install
```
now you have draw2d.js, jequery, raphael,...in the right version in your project.


##Install dependencies for the Gruntfile.js
```
npm install
```

##Build the project
Just type:
```
grunt
```
and you find the result in the **dist** folder.


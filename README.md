Day One Boilerplate (work in progress)
===========
A simple starter boilerplate for front-end development utilizing:

* [Grunt](http://gruntjs.com/)
* [SCSS](http://sass-lang.com/)
* [Bootstrap](http://getbootstrap.com/)
* [Font Awesome](http://fortawesome.github.io/Font-Awesome/)
* [Gridlover](http://www.gridlover.net/)
* [Velocity](http://julian.com/research/velocity/)

Requirements
-------------
[NodeJS](http://nodejs.org/) and [Grunt](http://gruntjs.com/).

Installing
-------------
Step 1. Install NodeJS by downloading it [here](http://nodejs.org/download/)

Step 2. Install Grunt CLI
```shell
npm install -g grunt-cli
```

Step 3. Install all the npm dependencies you need for Grunt.
```shell
cd to/root/folder
npm install
```

Step 4. All done! You can now run either `grunt` or `grunt dist` depending on your needs, and Grunt will do the rest for you.

Folder structure
-------------
The development will be done in `/source/js/` and `/source/scss/` which then will be compiled/concatinated/minified into `/build/js` and `/build/css`.

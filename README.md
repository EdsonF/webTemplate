WebTemplate
===================

# Why ?
If you often create new web projects, you know how long it can be to start from scratch.
You just need to kick start your project ? This repo has been made for you !

# What's in the magic box ?
Here, i propose my basic configuration for a website with :
* Bootstrap
* Less
* Angular (+ angular-route, angular-animate, angular-ui).
* (Grunt to compile in a clean final dist)

I used npm for project dependencies : 

* Dependencies (minimal node server to run your project)
	* connect
	* serve-static
* DevDependencies
	* grunt
	* grunt-contrib-clean
	* grunt-contrib-copy
	* grunt-contrib-cssmin
	* grunt-contrib-less
	* grunt-text-replace
	* time-grunt

# How to start ?
When you start a new project from this archetype :

- *[optional]* Run "**npm update -g**"
  This allows you to update all the npm global packages.

- [optional] Run "**npm install -g npm-check-updates**"
  This allows you to update all the npm packages of this project.

- [optional] Run "**npm-check-updates -u**"
  This will update the package.json dependencies to the latests available versions.

- Run "**npm install**"
  This will install all the required dependencies.

- Run "**node server.js**"
  To run the server, as simple as that.

- [optional] Run "**npm install -g bower**"
  If you don't have bower installed, this is going to install it globally.

# Dev is done and you're moving to prod env ? Sure !
A Grunt file has been prepared for you !
No need to worry about concating css, compiling js, optimizing your pics, ...
Just run "**grunt**" with your favourite terminal from the root of the project.
A "dist" folder will be created. You're ready !

# Quick custom
Before you really start your own projet, i recommend you to search for "CUSTOM" occurrences in the project.
Everything with CUSTOM is something you may want to change (except into "bower_components" folder).

# Contribution
I think the project has a nice & clean structure.
If you have better ideas i would be glad to hear from you and why not propose a pull request ... ;)
(Tho, it's only my second public repo on github i have no idea how pull request works, be kind and comprehensive if i make some mistakes).

Cheers !
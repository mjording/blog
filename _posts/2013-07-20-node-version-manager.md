---
layout: post
title: "Node Version Manager"
description: ""
category: 
tags: []
---
{% include JB/setup %}

As I have been spending a bit more time with node.js the need has come to work with different versions of node. 
 
Version management should be a familiar concept to most ruby/rails developers, especially those of us who have been developing on os x. If your a osx ruby developer chances are your using [Ruby Version Manager (RVM)](https://rvm.io) or [rbenv](https://github.com/sstephenson/rbenv). 

Enter the [Node Version Manager (NVM)](https://github.com/creationix/nvm). After calling the curl install script you'll be able to quickly change versions of Node to try out new features like [yield](http://blog.alexmaccaw.com/how-yield-will-transform-node). Simply call

	nvm install 0.11.2
	 
and voila your npm and node commands are now mapped to the current development release.

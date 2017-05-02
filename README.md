# em-webfiles-directory

[![Greenkeeper badge](https://badges.greenkeeper.io/eventEmitter/em-webfiles-directory.svg)](https://greenkeeper.io/)

directory representation for ee-webfiles

## installation

	npm install em-webfiles-directory

## build status

[![Build Status](https://travis-ci.org/eventEmitter/em-webfiles-directory.png?branch=master)](https://travis-ci.org/eventEmitter/em-webfiles-directory)


## usage

	var WebfilesDirecotry = require('em-webfiles-directory');


	var dir = new WebfilesDirecotry();

	dir.isDirectory(); //true

	Object.keys(dir); // []
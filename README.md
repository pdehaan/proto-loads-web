proto-loads-web
===============
proto-loads-web contains content for mocking a loads-web, version 2

## Description
contains mockups of:
- old-loads-web (loads-web, v1): static pages scraped from a python (bottle) based web framework
- proto-loads-web (loads-web, v2): zurb foundation mockups
- hapi (loads-web, v2): hapi web framework for loads-web v2

## TODO
- link together mockups/v1, so we can see a static version
- add static content to mockups/v2, so we can improve navigation & format reports, etc.
- setup a demo person login under features-demo

## hapi

Install
```
$ cd into hapi directory
$ npm install
```

Start mongodb
- open 2 terminal windows
- in one, start the mongodb service (the service will terminate when you close the window)
```
$ /usr/local/bin/mongod
```
- in another, start hapi
```
$ node server.js
```

## Reference
hapi framework
Created using [Hapi-Mode](https://github.com/dev0x10/Hapi-Mode): HapiJS, MongoDB for NodeJS

Hapi-Mode is a boilerplate similar like [MeanIO](http://mean.io/) but using different libraries.
Hapi-Mode trying to create a very minimal boilerplate in order to allow developers make changes to suit their needs without changing many lines of code.

##Packages
* [HapiJS](https://github.com/spumko/hapi)
* [Mongoose](http://mongoosejs.com/)
* [Zurb Foundation](http://foundation.zurb.com/)
* [AngularJS](https://angularjs.org/)

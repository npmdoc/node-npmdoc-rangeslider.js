# npmdoc-rangeslider.js

#### api documentation for  [rangeslider.js (v2.3.0)](https://github.com/andreruffert/rangeslider.js)  [![npm package](https://img.shields.io/npm/v/npmdoc-rangeslider.js.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-rangeslider.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-rangeslider.js.svg)](https://travis-ci.org/npmdoc/node-npmdoc-rangeslider.js)

#### Simple, small and fast JavaScript/jQuery polyfill for the HTML5 <input type="range"> slider element

[![NPM](https://nodei.co/npm/rangeslider.js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/rangeslider.js)

- [https://npmdoc.github.io/node-npmdoc-rangeslider.js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-rangeslider.js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rangeslider.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rangeslider.js/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-rangeslider.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-rangeslider.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "rangeslider.js",
    "title": "rangeslider.js",
    "description": "Simple, small and fast JavaScript/jQuery polyfill for the HTML5 <input type=\"range\"> slider element",
    "version": "2.3.0",
    "codename": "Navy Blue",
    "main": "dist/rangeslider.js",
    "homepage": "https://github.com/andreruffert/rangeslider.js",
    "author": {
        "name": "André Ruffert",
        "url": "http://andreruffert.com"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/andreruffert/rangeslider.js.git"
    },
    "keywords": [
        "input",
        "range",
        "slider",
        "rangeslider",
        "rangeslider.js",
        "polyfill",
        "browser",
        "jquery-plugin",
        "ui"
    ],
    "license": {
        "type": "MIT",
        "url": "https://github.com/andreruffert/rangeslider.js/blob/master/LICENSE.md"
    },
    "bugs": {
        "url": "https://github.com/andreruffert/rangeslider.js/issues"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "dependencies": {
        "jquery": ">=1.9.0"
    },
    "devDependencies": {
        "crayola": "0.0.1",
        "grunt": "~0.4.5",
        "grunt-bump": "0.3.1",
        "grunt-contrib-compass": "~1.0.3",
        "grunt-contrib-concat": "~0.5.1",
        "grunt-contrib-jshint": "~0.11.2",
        "grunt-contrib-uglify": "~0.9.1",
        "grunt-contrib-watch": "~0.6.1",
        "http-server": "^0.8.0",
        "jshint-stylish": "~2.0.1",
        "live-reload": "^1.1.0",
        "load-grunt-tasks": "~3.2.0",
        "parallelshell": "^2.0.0",
        "time-grunt": "~1.2.1"
    },
    "scripts": {
        "test": "grunt jshint",
        "static-server": "http-server -p 8080 ./ -s -o",
        "livereload": "live-reload --port 8081 dist/",
        "serve": "parallelshell 'npm run static-server' 'npm run livereload' 'grunt watch'",
        "start": "grunt build && npm run serve -s",
        "build": "grunt build"
    },
    "files": [
        "dist"
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

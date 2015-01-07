ngCordovaHTTP
=============

AngularJS module wrapper for [cordovaHTTP](https://github.com/panta/cordova-HTTP).

## Installation

You can use bower:

    bower install ngCordovaHTTP --save-dev

## Usage

### AngularJS

This plugin creates a `cordovaHTTP` service inside of a `ngCordovaHTTP` module.  You must load the module when you create your app's module.

    var app = angular.module('myApp', ['ngRoute', 'ngAnimate', 'ngCordovaHTTP']);
    
You can then inject the `cordovaHTTP` service into your controllers.  The functions can then be used identically to the examples shown for [cordovaHTTP](https://github.com/panta/cordova-HTTP) except that instead of accepting success and failure callback functions, each function returns a promise.  For more information on promises in AngularJS read the [AngularJS docs](http://docs.angularjs.org/api/ng/service/$q).  For more info on promises in general check out this article on [html5rocks](http://www.html5rocks.com/en/tutorials/es6/promises/).  Make sure that you load cordova.js or phonegap.js after AngularJS is loaded.

## License

The MIT License

Copyright (c) 2014 Wymsee, Inc

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

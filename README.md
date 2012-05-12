PROJECTNAME
========

DESCRIPTION

### Usage ###

```javascript
require([ 'PROJECTNAME' ], function ( PROJECTNAME ) {

});
```

### Building ###

Building requires Grunt.js be installed

If you are using NPM, install it with

```
npm install -g grunt
```

The build process generates a minified file named `main.js` in the root of the project.
The reason for this is that RequireJS and the Dojo Loader look for `main.js` unless otherwise specified.
This is mainly for cloning this repo directly and not using CPM.

### Change Log ###

2012 05 11 - **Removed CoffeeScript + build file and added Grunt.js**

* Use Grunt.js for build process and no more Coffee

2012 02 19 - **Modified For My Use**

* Tweak commonjs-package-template to better suit my needs

### License ###
The MIT License

Copyright (c) 2012 Blaine Bublitz <blaine@iceddev.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

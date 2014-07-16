[![view on npm](http://img.shields.io/npm/v/handlebars-json.svg)](https://www.npmjs.org/package/handlebars-json)
[![npm module downloads per month](http://img.shields.io/npm/dm/handlebars-json.svg)](https://www.npmjs.org/package/handlebars-json)
[![Build Status](https://travis-ci.org/75lb/handlebars-json.svg?branch=master)](https://travis-ci.org/75lb/handlebars-json)
[![Dependency Status](https://david-dm.org/75lb/handlebars-json.svg)](https://david-dm.org/75lb/handlebars-json)

#handlebars-json
Provides access to JSON.stringify from a Handlebars template. Useful when templating JSON files, e.g. 

```json
{
  "someProperty": {{{json-stringify someValue}}}
}
```

##Install
```sh
$ npm install handlebars-json --save
```
*Mac / Linux users may need to run with `sudo`*.

*documented by [jsdoc-to-markdown](https://github.com/75lb/jsdoc-to-markdown)*
# npmdoc-memwatch

#### api documentation for  memwatch (v0.2.2)  [![npm package](https://img.shields.io/npm/v/npmdoc-memwatch.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-memwatch) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-memwatch.svg)](https://travis-ci.org/npmdoc/node-npmdoc-memwatch)

#### Keep an eye on your memory usage, and discover and isolate leaks.

[![NPM](https://nodei.co/npm/memwatch.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/memwatch)

- [https://npmdoc.github.io/node-npmdoc-memwatch/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-memwatch/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-memwatch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-memwatch/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-memwatch/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-memwatch/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "memwatch",
    "description": "Keep an eye on your memory usage, and discover and isolate leaks.",
    "version": "0.2.2",
    "author": "Lloyd Hilaiel (http://lloyd.io)",
    "engines": {
        "node": ">= 0.6.0"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/lloyd/node-memwatch.git"
    },
    "main": "include.js",
    "licenses": [
        {
            "type": "wtfpl"
        }
    ],
    "bugs": {
        "url": "https://github.com/lloyd/node-memwatch/issues"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "test": "mocha tests"
    },
    "devDependencies": {
        "mocha": "1.2.2",
        "should": "0.6.3",
        "node-gyp": "0.5.7"
    },
    "contributors": [
        "Jed Parsons (@jedp)",
        "Jeff Haynie (@jhaynie)",
        "Justin Matthews (@jmatthewsr-ms)"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

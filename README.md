# npmdoc-dependo

#### api documentation for  [dependo (v0.1.6)](https://github.com/auchenberg/dependo.git)  [![npm package](https://img.shields.io/npm/v/npmdoc-dependo.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-dependo) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-dependo.svg)](https://travis-ci.org/npmdoc/node-npmdoc-dependo)

#### Visualize your CommonJS, AMD, or ES6 module dependencies.

[![NPM](https://nodei.co/npm/dependo.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/dependo)

- [https://npmdoc.github.io/node-npmdoc-dependo/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-dependo/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-dependo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-dependo/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-dependo/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-dependo/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "dependo",
    "version": "0.1.6",
    "author": "Kenneth Auchecnberg <kenneth@auchenberg.dk>",
    "repository": "https://github.com/auchenberg/dependo.git",
    "homepage": "https://github.com/auchenberg/dependo.git",
    "licenses": [
        {
            "type": "MIT"
        }
    ],
    "description": "Visualize your CommonJS, AMD, or ES6 module dependencies.",
    "keywords": [
        "AMD",
        "RequireJS",
        "require",
        "graph",
        "commonjs",
        "module",
        "circular",
        "dependency",
        "dependencies",
        "visualize",
        "D3",
        "es6"
    ],
    "engines": [
        "node >= 0.10.0"
    ],
    "dependencies": {
        "commander": "~2.6.0",
        "madge": "~0.5.0",
        "sha-1": "^0.1.1",
        "underscore": "~1.7.0"
    },
    "main": "./lib/dependo",
    "bin": {
        "dependo": "./bin/dependo"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

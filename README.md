# npmdoc-fv

#### api documentation for  [fv (v0.0.16)](https://github.com/creatale/node-fv)  [![npm package](https://img.shields.io/npm/v/npmdoc-fv.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-fv) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-fv.svg)](https://travis-ci.org/npmdoc/node-npmdoc-fv)

#### FormVision is a node.js library for extracting data from scanned forms

[![NPM](https://nodei.co/npm/fv.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/fv)

- [https://npmdoc.github.io/node-npmdoc-fv/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-fv/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-fv/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-fv/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-fv/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-fv/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "fv",
    "version": "0.0.16",
    "description": "FormVision is a node.js library for extracting data from scanned forms",
    "keywords": [
        "graphics",
        "vision",
        "barcode",
        "barcodes",
        "ocr",
        "omr",
        "checkbox",
        "checkboxes",
        "form",
        "forms"
    ],
    "homepage": "https://github.com/creatale/node-fv",
    "bugs": {
        "url": "https://github.com/creatale/node-fv/issues"
    },
    "author": "Christoph Schulz <christoph.schulz@creatale.de>",
    "contributors": [
        "Wolfgang Fellger <wolfgang.fellger@creatale.de>"
    ],
    "main": "./lib/index",
    "repository": {
        "type": "git",
        "url": "git://github.com/creatale/node-fv.git"
    },
    "dependencies": {
        "async": "^1.3.0",
        "dv": "1.9.4",
        "minimist": "^1.1.0",
        "glob": "^5.0.12"
    },
    "devDependencies": {
        "chai": "^3",
        "coffee-coverage": "^0.6.2",
        "coffee-script": "^1.8.0",
        "mocha": "^2.3.3"
    },
    "scripts": {
        "prepublish": "cake build",
        "test": "node_modules/.bin/mocha"
    },
    "license": "MIT",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# npmdoc-pbkdf2

#### api documentation for  [pbkdf2 (v3.0.9)](https://github.com/crypto-browserify/pbkdf2)  [![npm package](https://img.shields.io/npm/v/npmdoc-pbkdf2.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-pbkdf2) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-pbkdf2.svg)](https://travis-ci.org/npmdoc/node-npmdoc-pbkdf2)

#### This library provides the functionality of PBKDF2 with the ability to use any supported hashing algorithm returned from crypto.getHashes()

[![NPM](https://nodei.co/npm/pbkdf2.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pbkdf2)

- [https://npmdoc.github.io/node-npmdoc-pbkdf2/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pbkdf2/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pbkdf2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pbkdf2/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-pbkdf2/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-pbkdf2/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "pbkdf2",
    "version": "3.0.9",
    "description": "This library provides the functionality of PBKDF2 with the ability to use any supported hashing algorithm returned from crypto.getHashes()",
    "keywords": [
        "pbkdf2",
        "kdf",
        "salt",
        "hash"
    ],
    "homepage": "https://github.com/crypto-browserify/pbkdf2",
    "bugs": {
        "url": "https://github.com/crypto-browserify/pbkdf2/issues"
    },
    "license": "MIT",
    "author": "Daniel Cousens",
    "browser": "browser.js",
    "files": [
        "browser.js",
        "index.js",
        "node-shim-async.js",
        "node-shim.js",
        "precondition.js"
    ],
    "main": "index.js",
    "repository": {
        "type": "git",
        "url": "https://github.com/crypto-browserify/pbkdf2.git"
    },
    "scripts": {
        "prepublish": "npm run test",
        "coverage": "nyc --check-coverage --branches 90 --functions 100 tape test/*.js",
        "lint": "standard",
        "test": "npm run lint && npm run unit",
        "bundle-test": "browserify test/index.js > test/bundle.js",
        "unit": "tape test/*.js"
    },
    "devDependencies": {
        "browserify": "*",
        "nyc": "^6.4.0",
        "standard": "*",
        "tape": "^4.5.1"
    },
    "dependencies": {
        "create-hmac": "^1.1.2"
    },
    "standard": {
        "ignore": [
            "test/bundle.js"
        ]
    },
    "engines": {
        "node": ">=0.12"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

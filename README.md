# npmdoc-cloudant

#### api documentation for  [cloudant (v1.7.1)](http://github.com/cloudant/nodejs-cloudant)  [![npm package](https://img.shields.io/npm/v/npmdoc-cloudant.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-cloudant) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-cloudant.svg)](https://travis-ci.org/npmdoc/node-npmdoc-cloudant)

#### Cloudant Node.js client

[![NPM](https://nodei.co/npm/cloudant.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cloudant)

- [https://npmdoc.github.io/node-npmdoc-cloudant/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cloudant/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cloudant/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cloudant/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-cloudant/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-cloudant/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jason Smith"
    },
    "bugs": {
        "url": "https://github.com/cloudant/nodejs-cloudant/issues"
    },
    "contributors": [
        {
            "name": "Glynn Bird"
        }
    ],
    "dependencies": {
        "async": "2.1.2",
        "cloudant-nano": "6.4.1",
        "debug": "2.2.0",
        "request": "2.76.0"
    },
    "description": "Cloudant Node.js client",
    "devDependencies": {
        "dotenv": "2.0.0",
        "mocha": "3.1.2",
        "nock": "9.0.0",
        "should": "6.0.3"
    },
    "directories": {},
    "dist": {
        "shasum": "d52c4328eec7109a806c4a9c1d08243f7342d737",
        "tarball": "https://registry.npmjs.org/cloudant/-/cloudant-1.7.1.tgz"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "gitHead": "410638395b32b144ca3e0e83e0ccd8cca4728464",
    "homepage": "http://github.com/cloudant/nodejs-cloudant",
    "keywords": [
        "cloudant",
        "couchdb",
        "json",
        "nosql",
        "database"
    ],
    "license": "Apache-2.0",
    "main": "./cloudant.js",
    "maintainers": [
        {
            "name": "jhs"
        },
        {
            "name": "glynnbird"
        },
        {
            "name": "mikerhodes"
        }
    ],
    "name": "cloudant",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/cloudant/nodejs-cloudant.git"
    },
    "scripts": {
        "test": "mocha tests/*.js",
        "test-live": "NOCK_OFF=true mocha --timeout=5000 tests/*.js",
        "test-live-verbose": "env DEBUG='*,-mocha:*' npm run test-live",
        "test-verbose": "env DEBUG='*,-mocha:*' npm run test"
    },
    "version": "1.7.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

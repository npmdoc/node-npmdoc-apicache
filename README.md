# npmdoc-apicache

#### api documentation for  [apicache (v0.8.4)](https://github.com/kwhitley/apicache#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-apicache.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-apicache) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-apicache.svg)](https://travis-ci.org/npmdoc/node-npmdoc-apicache)

#### An ultra-simplified API response caching middleware for Express/Node using plain-english durations.

[![NPM](https://nodei.co/npm/apicache.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/apicache)

- [https://npmdoc.github.io/node-npmdoc-apicache/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-apicache/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-apicache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-apicache/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-apicache/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-apicache/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kevin R. Whitley",
        "url": "http://krwhitley.com"
    },
    "bugs": {
        "url": "https://github.com/kwhitley/apicache/issues"
    },
    "dependencies": {},
    "description": "An ultra-simplified API response caching middleware for Express/Node using plain-english durations.",
    "devDependencies": {
        "chai": "^3.5.0",
        "compression": "^1.6.2",
        "express": "^4.14.0",
        "fakeredis": "^1.0.3",
        "mocha": "^3.0.2",
        "restify": "^4.3.0",
        "restify-etag-cache": "^1.0.10",
        "supertest": "^2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "250e3e06c5d9cfb0d941532014bee9f1d5bc5191",
        "tarball": "https://registry.npmjs.org/apicache/-/apicache-0.8.4.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "57f870da3561b6ae888fc5f72c9552b4bb4bfa43",
    "homepage": "https://github.com/kwhitley/apicache#readme",
    "keywords": [
        "cache",
        "API",
        "redis",
        "memcache",
        "response",
        "express",
        "JSON",
        "duration",
        "middleware",
        "memory"
    ],
    "license": "MIT",
    "main": "./src/apicache.js",
    "maintainers": [
        {
            "name": "kwhitley"
        },
        {
            "name": "nmors"
        },
        {
            "name": "tskillian"
        }
    ],
    "name": "apicache",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kwhitley/apicache.git"
    },
    "scripts": {
        "dev": "npm run test -- --watch",
        "prepublish": "npm run test",
        "test": "mocha $(find test -name '*.test.js') --recursive"
    },
    "version": "0.8.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

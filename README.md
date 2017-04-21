# npmdoc-apicache

#### api documentation for  apicache (v0.8.4)  [![npm package](https://img.shields.io/npm/v/npmdoc-apicache.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-apicache) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-apicache.svg)](https://travis-ci.org/npmdoc/node-npmdoc-apicache)

#### An ultra-simplified API response caching middleware for Express/Node using plain-english durations.

[![NPM](https://nodei.co/npm/apicache.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/apicache)

- [https://npmdoc.github.io/node-npmdoc-apicache/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-apicache/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-apicache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-apicache/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-apicache/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-apicache/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "apicache",
    "version": "0.8.4",
    "scripts": {
        "test": "mocha $(find test -name '*.test.js') --recursive",
        "dev": "npm run test -- --watch",
        "prepublish": "npm run test"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "description": "An ultra-simplified API response caching middleware for Express/Node using plain-english durations.",
    "main": "./src/apicache.js",
    "repository": {
        "type": "git",
        "url": "https://github.com/kwhitley/apicache.git"
    },
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
    "author": "Kevin R. Whitley <kevin3503@gmail.com> (http://krwhitley.com)",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/kwhitley/apicache/issues"
    },
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
    "dependencies": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

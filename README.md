# npmdoc-koa-body

#### basic api documentation for  [koa-body (v1.6.0)](https://github.com/dlau/koa-body#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-koa-body.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-koa-body) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-koa-body.svg)](https://travis-ci.org/npmdoc/node-npmdoc-koa-body)

#### A koa body parser middleware. Support multipart, urlencoded and json request bodies.

[![NPM](https://nodei.co/npm/koa-body.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/koa-body)

- [https://npmdoc.github.io/node-npmdoc-koa-body/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-koa-body/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-koa-body/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-koa-body/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-koa-body/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-koa-body/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Daryl Lau",
        "url": "https://github.com/dlau"
    },
    "bugs": {
        "url": "https://github.com/dlau/koa-body/issues"
    },
    "contributors": [
        {
            "name": "Daryl Lau",
            "url": "https://github.com/dlau"
        },
        {
            "name": "Charlike Mike Reagent",
            "url": "https://github.com/tunnckoCore"
        }
    ],
    "dependencies": {
        "co-body": "*",
        "extend": "1.3.0",
        "formidable": "1.0.17"
    },
    "description": "A koa body parser middleware. Support multipart, urlencoded and json request bodies.",
    "devDependencies": {
        "koa": "*",
        "koa-resource-router": "*",
        "koa-router": "*",
        "lodash": "^3.3.1",
        "mocha": "*",
        "multiline": "*",
        "should": "*",
        "supertest": "2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "2e44d7c9ee1b55e2a995c32145cb874e4dbe29ae",
        "tarball": "https://registry.npmjs.org/koa-body/-/koa-body-1.6.0.tgz"
    },
    "files": [
        ".gitignore",
        ".npmignore",
        ".travis.yml",
        "LICENSE",
        "Makefile",
        "README.md",
        "example.js",
        "index.js",
        "test.js"
    ],
    "gitHead": "51e1c98dc23810a5b731a81b899e7f0f4d893a52",
    "homepage": "https://github.com/dlau/koa-body#readme",
    "keywords": [
        "koa",
        "urlencoded",
        "multipart",
        "json",
        "body",
        "parser",
        "form"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "dlau"
        }
    ],
    "name": "koa-body",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/dlau/koa-body.git"
    },
    "scripts": {
        "examples-koa-router": "node --harmony examples/koa-router.js",
        "examples-multer": "node --harmony examples/multer.js",
        "test": "mocha --harmony"
    },
    "version": "1.6.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

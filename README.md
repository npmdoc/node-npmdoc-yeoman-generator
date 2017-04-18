# npmdoc-yeoman-generator

#### api documentation for  [yeoman-generator (v1.1.1)](http://yeoman.io)  [![npm package](https://img.shields.io/npm/v/npmdoc-yeoman-generator.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-yeoman-generator) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-yeoman-generator.svg)](https://travis-ci.org/npmdoc/node-npmdoc-yeoman-generator)

#### Rails-inspired generator system that provides scaffolding for your apps

[![NPM](https://nodei.co/npm/yeoman-generator.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/yeoman-generator)

- [https://npmdoc.github.io/node-npmdoc-yeoman-generator/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-yeoman-generator/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-yeoman-generator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-yeoman-generator/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-yeoman-generator/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-yeoman-generator/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Yeoman"
    },
    "bugs": {
        "url": "https://github.com/yeoman/generator/issues"
    },
    "dependencies": {
        "async": "^2.0.0",
        "chalk": "^1.0.0",
        "class-extend": "^0.1.0",
        "cli-table": "^0.3.1",
        "cross-spawn": "^5.0.1",
        "dargs": "^5.1.0",
        "dateformat": "^2.0.0",
        "debug": "^2.1.0",
        "detect-conflict": "^1.0.0",
        "error": "^7.0.2",
        "find-up": "^2.1.0",
        "github-username": "^3.0.0",
        "glob": "^7.0.3",
        "istextorbinary": "^2.1.0",
        "lodash": "^4.11.1",
        "mem-fs-editor": "^3.0.0",
        "minimist": "^1.2.0",
        "mkdirp": "^0.5.0",
        "path-exists": "^3.0.0",
        "path-is-absolute": "^1.0.0",
        "pretty-bytes": "^4.0.2",
        "read-chunk": "^2.0.0",
        "read-pkg-up": "^2.0.0",
        "rimraf": "^2.2.0",
        "run-async": "^2.0.0",
        "shelljs": "^0.7.0",
        "text-table": "^0.2.0",
        "through2": "^2.0.0",
        "user-home": "^2.0.0",
        "yeoman-environment": "^1.1.0"
    },
    "description": "Rails-inspired generator system that provides scaffolding for your apps",
    "devDependencies": {
        "gulp": "^3.6.0",
        "gulp-coveralls": "^0.1.0",
        "gulp-istanbul": "^1.0.0",
        "gulp-mocha": "^3.0.1",
        "gulp-nsp": "^2.1.0",
        "gulp-plumber": "^1.0.0",
        "inquirer": "^3.0.1",
        "jsdoc": "^3.3.0-beta1",
        "mockery": "^2.0.0",
        "nock": "^9.0.5",
        "pinkie-promise": "^2.0.0",
        "proxyquire": "^1.0.0",
        "sinon": "^1.9.1",
        "tui-jsdoc-template": "^1.0.4",
        "xo": "^0.16.0",
        "yeoman-assert": "^3.0.0",
        "yeoman-test": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "40c2b4f6cdfbe05e1952fdd72933f0d8925dbdf5",
        "tarball": "https://registry.npmjs.org/yeoman-generator/-/yeoman-generator-1.1.1.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "lib"
    ],
    "gitHead": "80863b0aaab16794c46acfe4ca013a98d5887185",
    "homepage": "http://yeoman.io",
    "keywords": [
        "development",
        "dev",
        "build",
        "tool",
        "cli",
        "scaffold",
        "scaffolding",
        "generate",
        "generator",
        "yeoman",
        "app"
    ],
    "license": "BSD-2-Clause",
    "main": "lib",
    "maintainers": [
        {
            "name": "addyosmani"
        },
        {
            "name": "eddiemonge"
        },
        {
            "name": "mischah"
        },
        {
            "name": "passy"
        },
        {
            "name": "paulirish"
        },
        {
            "name": "sboudrias"
        },
        {
            "name": "sindresorhus"
        }
    ],
    "name": "yeoman-generator",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/yeoman/generator.git"
    },
    "scripts": {
        "doc": "jsdoc -c jsdoc.json",
        "prepublish": "gulp prepublish",
        "test": "xo && gulp"
    },
    "version": "1.1.1",
    "xo": {
        "esnext": false,
        "space": true,
        "rules": {
            "quote-props": "off",
            "import/newline-after-import": "off"
        },
        "overrides": [
            {
                "files": "test/**",
                "envs": [
                    "node",
                    "mocha"
                ]
            }
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

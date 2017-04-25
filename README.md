# npmdoc-highlights

#### basic api documentation for  [highlights (v3.0.1)](https://github.com/atom/highlights)  [![npm package](https://img.shields.io/npm/v/npmdoc-highlights.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-highlights) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-highlights.svg)](https://travis-ci.org/npmdoc/node-npmdoc-highlights)

#### Syntax highlighter

[![NPM](https://nodei.co/npm/highlights.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/highlights)

- [https://npmdoc.github.io/node-npmdoc-highlights/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-highlights/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-highlights/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-highlights/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-highlights/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-highlights/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "highlights": "bin/highlights"
    },
    "bugs": {
        "url": "https://github.com/atom/highlights/issues"
    },
    "dependencies": {
        "first-mate": "^7.0.2",
        "first-mate-select-grammar": "^1.0.1",
        "fs-plus": "^3.0.0",
        "once": "^1.3.2",
        "season": "^6.0.0",
        "underscore-plus": "^1.5.1",
        "yargs": "^4.7.1"
    },
    "description": "Syntax highlighter",
    "devDependencies": {
        "grunt": "^1.0.1",
        "grunt-cli": "^1.2.0",
        "grunt-coffeelint": "0.0.16",
        "grunt-contrib-coffee": "^1.0.0",
        "grunt-shell": "^1.3.0",
        "jasmine-focused": "^1.0.4",
        "language-erlang": "^2.0.0",
        "standard-version": "^2.3.1"
    },
    "directories": {},
    "dist": {
        "shasum": "1687eed9975c49fe4a33d4c0d5e8df9ad6104432",
        "tarball": "https://registry.npmjs.org/highlights/-/highlights-3.0.1.tgz"
    },
    "gitHead": "15d2d9c8cfda9f679637695658100885c336ea3f",
    "homepage": "https://github.com/atom/highlights",
    "license": "MIT",
    "main": "lib/highlights.js",
    "maintainers": [
        {
            "name": "as-cii"
        },
        {
            "name": "atom"
        },
        {
            "name": "bcoe"
        },
        {
            "name": "benogle"
        },
        {
            "name": "kevinsawicki"
        },
        {
            "name": "maxbrunsfeld"
        },
        {
            "name": "nathansobo"
        },
        {
            "name": "soldair"
        },
        {
            "name": "zcbenz"
        }
    ],
    "name": "highlights",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/atom/highlights.git"
    },
    "scripts": {
        "prepublish": "grunt prepublish",
        "pretest": "git submodule update --init --recursive",
        "test": "grunt test",
        "version": "standard-version"
    },
    "version": "3.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

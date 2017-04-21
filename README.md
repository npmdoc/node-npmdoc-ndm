# npmdoc-ndm

#### api documentation for  ndm (v3.11.3)  [![npm package](https://img.shields.io/npm/v/npmdoc-ndm.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ndm) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ndm.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ndm)

#### ndm allows you to deploy OS-specific service-wrappers directly from npm-packages.

[![NPM](https://nodei.co/npm/ndm.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ndm)

- [https://npmdoc.github.io/node-npmdoc-ndm/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ndm/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ndm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ndm/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ndm/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ndm/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ndm",
    "version": "3.11.3",
    "description": "ndm allows you to deploy OS-specific service-wrappers directly from npm-packages.",
    "main": "./lib/index.js",
    "bin": "./bin/ndm.js",
    "scripts": {
        "test": "lab -c -v --timeout 8000 --ignore Intl,Map,Set"
    },
    "author": "Ben Coe <ben@npmjs.com>",
    "license": "ISC",
    "dependencies": {
        "async": "^0.9.0",
        "chalk": "^0.5.1",
        "ejs": "^1.0.0",
        "inquirer": "^0.5.1",
        "lodash": "^2.4.1",
        "mkdirp": "^0.5.0",
        "node-uuid": "^1.4.3",
        "npmconf": "^1.1.5",
        "rc": "^0.4.0",
        "rimraf": "^2.2.8",
        "string": "^1.8.1",
        "temp": "^0.8.1",
        "xml-escape": "^1.0.0",
        "yargs": "^3.25.0"
    },
    "devDependencies": {
        "lab": "~4.5.1",
        "mocha": "^1.20.0"
    },
    "repository": {
        "type": "git",
        "url": "git@github.com:npm/ndm.git"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

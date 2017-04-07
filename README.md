# api documentation for  [karma-spec-reporter (v0.0.30)](https://github.com/mlex/karma-spec-reporter#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-karma-spec-reporter.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-karma-spec-reporter) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-karma-spec-reporter.svg)](https://travis-ci.org/npmdoc/node-npmdoc-karma-spec-reporter)
#### A Karma plugin. Report all spec-results to console (like mocha's spec reporter).

[![NPM](https://nodei.co/npm/karma-spec-reporter.png?downloads=true)](https://www.npmjs.com/package/karma-spec-reporter)

[![apidoc](https://npmdoc.github.io/node-npmdoc-karma-spec-reporter/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-karma-spec-reporter_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-karma-spec-reporter/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-karma-spec-reporter/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-karma-spec-reporter/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Michael Lex",
        "email": "michael.lex@codecentric.de"
    },
    "bugs": {
        "url": "https://github.com/mlex/karma-spec-reporter/issues"
    },
    "dependencies": {
        "colors": "^1.1.2"
    },
    "description": "A Karma plugin. Report all spec-results to console (like mocha's spec reporter).",
    "devDependencies": {
        "chai": "^3.4.0",
        "coveralls": "^2.11.4",
        "istanbul": "^0.4.0",
        "mocha-runner": "^1.1.1",
        "rewire": "^2.5.1",
        "sinon": "^1.17.2",
        "sinon-chai": "^2.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d10b5c8bb441cb1c6adf56785f89d395f2e9093a",
        "tarball": "https://registry.npmjs.org/karma-spec-reporter/-/karma-spec-reporter-0.0.30.tgz"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "404cb09db962452627e693587c1637d9db1c00aa",
    "homepage": "https://github.com/mlex/karma-spec-reporter#readme",
    "keywords": [
        "karma-plugin",
        "reporter"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "hdavidzhu",
            "email": "hdavidzhu@gmail.com"
        },
        {
            "name": "mlex",
            "email": "mich.lex@gmail.com"
        },
        {
            "name": "tmcgee123",
            "email": "mcgeehonstg@gmail.com"
        }
    ],
    "name": "karma-spec-reporter",
    "optionalDependencies": {},
    "peerDependencies": {
        "karma": ">=0.9"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/mlex/karma-spec-reporter.git"
    },
    "scripts": {
        "coverage": "istanbul cover -x 'test/**/*.js' ./node_modules/.bin/mocha-runner -- --reporter spec 'test/**/*.js'",
        "test": "mocha-runner --reporter spec 'test/**/*.spec.js'"
    },
    "version": "0.0.30"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module karma-spec-reporter](#apidoc.module.karma-spec-reporter)



# <a name="apidoc.module.karma-spec-reporter"></a>[module karma-spec-reporter](#apidoc.module.karma-spec-reporter)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

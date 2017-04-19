# npmdoc-karma-spec-reporter

#### api documentation for  [karma-spec-reporter (v0.0.31)](https://github.com/mlex/karma-spec-reporter#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-karma-spec-reporter.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-karma-spec-reporter) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-karma-spec-reporter.svg)](https://travis-ci.org/npmdoc/node-npmdoc-karma-spec-reporter)

#### A Karma plugin. Report all spec-results to console (like mocha's spec reporter).

[![NPM](https://nodei.co/npm/karma-spec-reporter.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/karma-spec-reporter)

- [https://npmdoc.github.io/node-npmdoc-karma-spec-reporter/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-karma-spec-reporter/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-karma-spec-reporter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-karma-spec-reporter/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-karma-spec-reporter/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-karma-spec-reporter/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Michael Lex"
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
        "mocha": "^3.2.0",
        "mocha-runner": "^1.1.1",
        "npm-run-all": "^4.0.2",
        "rewire": "^2.5.1",
        "sinon": "^1.17.2",
        "sinon-chai": "^2.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "4830dc7148a155c7d7a186e632339a0d80fadec3",
        "tarball": "https://registry.npmjs.org/karma-spec-reporter/-/karma-spec-reporter-0.0.31.tgz"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "ed403e7d423a769eb71e9283071ed125e00e30e5",
    "homepage": "https://github.com/mlex/karma-spec-reporter#readme",
    "keywords": [
        "karma-plugin",
        "reporter"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "hdavidzhu"
        },
        {
            "name": "mlex"
        },
        {
            "name": "tmcgee123"
        }
    ],
    "name": "karma-spec-reporter",
    "optionalDependencies": {},
    "peerDependencies": {
        "karma": ">=0.9"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/mlex/karma-spec-reporter.git"
    },
    "scripts": {
        "coverage": "istanbul cover -x test/**/*.js node_modules/mocha/bin/_mocha -- --reporter spec test/**/*.js",
        "coverage-report": "istanbul report",
        "precoverage-report": "run-s coverage",
        "test": "mocha-runner --reporter spec test/**/*.spec.js"
    },
    "version": "0.0.31"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

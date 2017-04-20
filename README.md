# npmtest-gulp-cdnizer

#### basic test coverage for  [gulp-cdnizer (v1.1.7)](https://github.com/OverZealous/gulp-cdnizer)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-cdnizer.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-cdnizer) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-cdnizer.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-cdnizer)

#### A gulp plugin for replacing local links with CDN links, includes fallbacks and customization

[![NPM](https://nodei.co/npm/gulp-cdnizer.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-cdnizer)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-cdnizer/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-cdnizer/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-cdnizer/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-cdnizer/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-cdnizer/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-cdnizer/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-cdnizer/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-cdnizer/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-cdnizer/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-cdnizer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-cdnizer/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-cdnizer/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-cdnizer/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-cdnizer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-cdnizer/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-cdnizer/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-cdnizer/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-cdnizer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-cdnizer/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-cdnizer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-cdnizer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Phil DeJarnett",
        "url": "https://github.com/OverZealous"
    },
    "bugs": {
        "url": "https://github.com/OverZealous/gulp-cdnizer/issues"
    },
    "dependencies": {
        "cdnizer": "^1.1.6",
        "gulp-util": "^3.0.0",
        "through2": "^0.5.1"
    },
    "description": "A gulp plugin for replacing local links with CDN links, includes fallbacks and customization",
    "devDependencies": {
        "coveralls": "*",
        "event-stream": "*",
        "istanbul": "*",
        "mocha": "*",
        "mocha-lcov-reporter": "*",
        "should": "~2.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "1787d562a7a81179e623051dc5eff71869e0ac78",
        "tarball": "https://registry.npmjs.org/gulp-cdnizer/-/gulp-cdnizer-1.1.7.tgz"
    },
    "engines": {
        "node": ">=0.8.0",
        "npm": ">=1.2.10"
    },
    "gitHead": "12ddf0ca8a8f4b5a53b37276a681e41d05364db9",
    "homepage": "https://github.com/OverZealous/gulp-cdnizer",
    "keywords": [
        "gulpplugin",
        "cdn"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "overzealous"
        }
    ],
    "name": "gulp-cdnizer",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/OverZealous/gulp-cdnizer.git"
    },
    "scripts": {
        "coveralls": "istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "test": "istanbul test _mocha --report html -- test/*.js --reporter spec"
    },
    "version": "1.1.7"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

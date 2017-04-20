# npmtest-enquire.js

#### basic test coverage for  [enquire.js (v2.1.6)](http://wicky.nillia.ms/enquire.js)  [![npm package](https://img.shields.io/npm/v/npmtest-enquire.js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-enquire.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-enquire.js.svg)](https://travis-ci.org/npmtest/node-npmtest-enquire.js)

#### Awesome Media Queries in JavaScript

[![NPM](https://nodei.co/npm/enquire.js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/enquire.js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-enquire.js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-enquire.js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-enquire.js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-enquire.js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-enquire.js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-enquire.js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-enquire.js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-enquire.js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-enquire.js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-enquire.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-enquire.js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-enquire.js/build/test-report.html](https://npmtest.github.io/node-npmtest-enquire.js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-enquire.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-enquire.js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-enquire.js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-enquire.js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-enquire.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-enquire.js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-enquire.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-enquire.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nick Williams",
        "url": "http://wicky.nillia.ms"
    },
    "bugs": {
        "url": "https://github.com/WickyNilliams/enquire.js/issues"
    },
    "dependencies": {},
    "description": "Awesome Media Queries in JavaScript",
    "devDependencies": {
        "bundle-collapser": "^1.2.1",
        "grunt": "^1.0.1",
        "grunt-browserify": "^5.0.0",
        "grunt-contrib-jshint": "^1.1.0",
        "grunt-contrib-uglify": "^2.2.0",
        "grunt-contrib-watch": "^1.0.0",
        "grunt-karma": "^2.0.0",
        "jasmine-core": "^2.5.2",
        "jshint-stylish": "^2.2.1",
        "karma": "^1.5.0",
        "karma-browserify": "^5.1.1",
        "karma-jasmine": "^1.1.0",
        "karma-phantomjs-launcher": "^1.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "3e8780c9b8b835084c3f60e166dbc3c2a3c89814",
        "tarball": "https://registry.npmjs.org/enquire.js/-/enquire.js-2.1.6.tgz"
    },
    "files": [
        "src",
        "dist"
    ],
    "gitHead": "2f339f1e29b2b6676f541e64b770635075af494d",
    "homepage": "http://wicky.nillia.ms/enquire.js",
    "keywords": [
        "media query",
        "media queries",
        "matchMedia",
        "enquire",
        "enquire.js"
    ],
    "license": "MIT",
    "main": "./src",
    "maintainers": [
        {
            "name": "wickynilliams"
        }
    ],
    "name": "enquire.js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/WickyNilliams/enquire.js.git"
    },
    "scripts": {
        "postversion": "git push origin master --tags && npm publish",
        "preversion": "npm test",
        "start": "grunt",
        "test": "grunt test",
        "version": "grunt build && git add ."
    },
    "version": "2.1.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

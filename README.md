# npmtest-blueimp-md5

#### basic test coverage for  [blueimp-md5 (v2.7.0)](https://github.com/blueimp/JavaScript-MD5)  [![npm package](https://img.shields.io/npm/v/npmtest-blueimp-md5.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-blueimp-md5) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-blueimp-md5.svg)](https://travis-ci.org/npmtest/node-npmtest-blueimp-md5)

#### JavaScript MD5 implementation. Compatible with server-side environments like Node.js, module loaders like RequireJS, Browserify or webpack and all web browsers.

[![NPM](https://nodei.co/npm/blueimp-md5.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/blueimp-md5)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-blueimp-md5/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-blueimp-md5/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-blueimp-md5/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-blueimp-md5/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-blueimp-md5/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-blueimp-md5/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-blueimp-md5/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-blueimp-md5/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-blueimp-md5/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-blueimp-md5/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-blueimp-md5/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-blueimp-md5/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-blueimp-md5/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-blueimp-md5/build/test-report.html](https://npmtest.github.io/node-npmtest-blueimp-md5/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-blueimp-md5/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-blueimp-md5/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-blueimp-md5/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-blueimp-md5/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-blueimp-md5/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-blueimp-md5/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-blueimp-md5/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-blueimp-md5/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sebastian Tschan",
        "url": "https://blueimp.net"
    },
    "bugs": {
        "url": "https://github.com/blueimp/JavaScript-MD5/issues"
    },
    "contributors": [
        {
            "name": "Paul Johnston",
            "url": "http://pajhome.org.uk/crypt/md5"
        }
    ],
    "dependencies": {},
    "description": "JavaScript MD5 implementation. Compatible with server-side environments like Node.js, module loaders like RequireJS, Browserify or webpack and all web browsers.",
    "devDependencies": {
        "chai": "3.5.0",
        "mocha": "3.1.0",
        "standard": "8.3.0",
        "uglify-js": "2.7.3"
    },
    "directories": {},
    "dist": {
        "shasum": "7f518e0dd70467fefe28ecba398916092f2a02a9",
        "tarball": "https://registry.npmjs.org/blueimp-md5/-/blueimp-md5-2.7.0.tgz"
    },
    "gitHead": "9756d82db70b0f678bc6cd055e7aa08f5c1a0390",
    "homepage": "https://github.com/blueimp/JavaScript-MD5",
    "keywords": [
        "javascript",
        "md5"
    ],
    "license": "MIT",
    "main": "js/md5.js",
    "maintainers": [
        {
            "name": "blueimp"
        }
    ],
    "name": "blueimp-md5",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/blueimp/JavaScript-MD5.git"
    },
    "scripts": {
        "build": "cd js && uglifyjs md5.js -c -m -o md5.min.js --source-map md5.min.js.map",
        "lint": "standard js/*.js test/*.js",
        "postversion": "git push --tags origin master master:gh-pages && npm publish",
        "preversion": "npm test",
        "test": "npm run lint && npm run unit",
        "unit": "mocha",
        "version": "npm run build && git add -A js"
    },
    "title": "JavaScript MD5",
    "version": "2.7.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

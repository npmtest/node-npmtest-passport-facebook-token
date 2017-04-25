# npmtest-passport-facebook-token

#### basic test coverage for  [passport-facebook-token (v3.3.0)](https://github.com/drudge/passport-facebook-token#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-passport-facebook-token.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-passport-facebook-token) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-passport-facebook-token.svg)](https://travis-ci.org/npmtest/node-npmtest-passport-facebook-token)

#### Facebook token authentication strategy for Passport

[![NPM](https://nodei.co/npm/passport-facebook-token.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/passport-facebook-token)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-passport-facebook-token/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-passport-facebook-token/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-passport-facebook-token/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-passport-facebook-token/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-passport-facebook-token/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-passport-facebook-token/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-passport-facebook-token/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-passport-facebook-token/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-passport-facebook-token/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-passport-facebook-token/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-passport-facebook-token/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-passport-facebook-token/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-passport-facebook-token/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-passport-facebook-token/build/test-report.html](https://npmtest.github.io/node-npmtest-passport-facebook-token/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-passport-facebook-token/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-passport-facebook-token/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-passport-facebook-token/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-passport-facebook-token/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-passport-facebook-token/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-passport-facebook-token/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-passport-facebook-token/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-passport-facebook-token/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nicholas Penree",
        "url": "http://www.penree.com/"
    },
    "bugs": {
        "url": "http://github.com/drudge/passport-facebook-token/issues"
    },
    "config": {
        "commitizen": {
            "path": "./node_modules/cz-conventional-changelog"
        }
    },
    "contributors": [
        {
            "name": "Eugene Obrezkov"
        }
    ],
    "dependencies": {
        "passport-oauth": "1.0.0"
    },
    "description": "Facebook token authentication strategy for Passport",
    "devDependencies": {
        "babel-cli": "6.4.5",
        "babel-plugin-add-module-exports": "0.1.2",
        "babel-preset-es2015": "6.3.13",
        "chai": "3.4.1",
        "chai-passport-strategy": "0.2.0",
        "coveralls": "2.11.6",
        "cz-conventional-changelog": "1.1.5",
        "isparta": "4.0.0",
        "mocha": "2.4.2",
        "sinon": "1.17.3"
    },
    "directories": {},
    "dist": {
        "shasum": "7404ca6fdd3790e11060cc60c562b21f0d0481ee",
        "tarball": "https://registry.npmjs.org/passport-facebook-token/-/passport-facebook-token-3.3.0.tgz"
    },
    "gitHead": "45f7f38c605dec7b89674c77c8616a2f19d27ad2",
    "homepage": "https://github.com/drudge/passport-facebook-token#readme",
    "keywords": [
        "passport",
        "facebook",
        "auth",
        "authn",
        "authentication",
        "identity"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "drudge"
        },
        {
            "name": "ghaiklor"
        }
    ],
    "name": "passport-facebook-token",
    "optionalDependencies": {},
    "publishConfig": {
        "tag": "latest"
    },
    "release": {
        "branch": "master"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/drudge/passport-facebook-token.git"
    },
    "scripts": {
        "compile": "babel src --out-dir lib",
        "coveralls": "cat coverage/lcov.info | coveralls",
        "prepublish": "npm run compile",
        "test": "babel-node ./node_modules/.bin/isparta cover _mocha"
    },
    "version": "3.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# npmtest-fis

#### basic test coverage for  [fis (v1.10.5)](http://fis.baidu.com/)  [![npm package](https://img.shields.io/npm/v/npmtest-fis.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-fis) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-fis.svg)](https://travis-ci.org/npmtest/node-npmtest-fis)

#### front-end integrated solution.

[![NPM](https://nodei.co/npm/fis.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/fis)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-fis/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-fis/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-fis/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-fis/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-fis/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-fis/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-fis/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-fis/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-fis/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-fis/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-fis/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-fis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-fis/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-fis/build/test-report.html](https://npmtest.github.io/node-npmtest-fis/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-fis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-fis/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-fis/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-fis/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-fis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-fis/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-fis/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-fis/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "FIS Team"
    },
    "bin": {
        "fis": "bin/fis"
    },
    "bugs": {
        "url": "https://github.com/fis-dev/fis/issues"
    },
    "dependencies": {
        "colors": "0.6.2",
        "commander": "1.3.2",
        "fis-command-install": "0.2.15",
        "fis-command-release": "0.13.0",
        "fis-command-server": "0.7.9",
        "fis-deploy-default": "0.1.3",
        "fis-kernel": "2.0.19",
        "fis-optimizer-clean-css": "0.0.9",
        "fis-optimizer-png-compressor": "0.1.6",
        "fis-optimizer-uglify-js": "0.1.14",
        "fis-packager-map": "0.0.9",
        "fis-postprocessor-jswrapper": "0.0.12",
        "fis-prepackager-derived": "0.0.3",
        "fis-preprocessor-components": "1.0.19",
        "fis-spriter-csssprites": "0.3.11"
    },
    "description": "front-end integrated solution.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "61ce1174074fcdef0073f47fdbd79b4fc4e91e22",
        "tarball": "https://registry.npmjs.org/fis/-/fis-1.10.5.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "gitHead": "19b38bc7be1d9198e421422e9e0b87bbc482c134",
    "homepage": "http://fis.baidu.com/",
    "keywords": [
        "fis"
    ],
    "license": "MIT",
    "main": "fis.js",
    "maintainers": [
        {
            "name": "fis-dev"
        },
        {
            "name": "fouber"
        },
        {
            "name": "fansekey"
        },
        {
            "name": "2betop"
        },
        {
            "name": "hefangshi"
        }
    ],
    "name": "fis",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/fis-dev/fis.git"
    },
    "scripts": {
        "test": "mocha test/ut --recursive",
        "uninstall": "node -e \"var cp = require('child_process'); cp.exec('bin/fis server stop');\""
    },
    "version": "1.10.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# npmtest-grunt-bowercopy

#### basic test coverage for  [grunt-bowercopy (v1.2.4)](https://github.com/timmywil/grunt-bowercopy)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-bowercopy.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-bowercopy) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-bowercopy.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-bowercopy)

#### Scrupulously manage file locations for bower dependencies.

[![NPM](https://nodei.co/npm/grunt-bowercopy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-bowercopy)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-bowercopy/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-bowercopy/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-bowercopy/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-bowercopy/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-bowercopy/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-bowercopy/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-bowercopy/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-bowercopy/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-bowercopy/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-bowercopy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-bowercopy/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-bowercopy/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-bowercopy/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-bowercopy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-bowercopy/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-bowercopy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-bowercopy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-bowercopy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-bowercopy/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-bowercopy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-bowercopy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "grunt-bowercopy",
    "version": "1.2.4",
    "description": "Scrupulously manage file locations for bower dependencies.",
    "homepage": "https://github.com/timmywil/grunt-bowercopy",
    "repository": {
        "type": "git",
        "url": "https://github.com/timmywil/grunt-bowercopy.git"
    },
    "bugs": "https://github.com/timmywil/grunt-bowercopy/issues",
    "author": {
        "name": "Timmy Willison",
        "url": "http://timmywillison.com"
    },
    "keywords": [
        "gruntplugin",
        "bowercopy",
        "bower",
        "copy"
    ],
    "engines": {
        "node": ">= 0.10.0"
    },
    "licenses": [
        {
            "type": "MIT"
        }
    ],
    "dependencies": {
        "bower": "^1.3.5",
        "glob": "^4.3.5",
        "lodash": "^3.1.0"
    },
    "devDependencies": {
        "grunt": "^0.4.5",
        "grunt-bump": "^0.1.0",
        "grunt-contrib-clean": "^0.6.0",
        "grunt-contrib-jshint": "^0.11.0",
        "grunt-contrib-nodeunit": "^0.4.0",
        "grunt-contrib-watch": "^0.6.1",
        "grunt-jsonlint": "^1.0.4",
        "load-grunt-tasks": "^3.1.0"
    },
    "scripts": {
        "test": "grunt test"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

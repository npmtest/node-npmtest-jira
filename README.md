# npmtest-jira

#### basic test coverage for  [jira (v0.9.2)](http://github.com/steves/node-jira)  [![npm package](https://img.shields.io/npm/v/npmtest-jira.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jira) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jira.svg)](https://travis-ci.org/npmtest/node-npmtest-jira)

#### Wrapper for the JIRA API

[![NPM](https://nodei.co/npm/jira.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jira)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jira/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jira/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jira/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jira/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jira/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jira/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jira/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jira/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jira/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jira/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jira/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jira/build/test-report.html](https://npmtest.github.io/node-npmtest-jira/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jira/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jira/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jira/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jira/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jira/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jira/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jira/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jira/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "jira",
    "version": "0.9.2",
    "description": "Wrapper for the JIRA API",
    "author": "Steven Surowiec <steven.surowiec@gmail.com>",
    "contributors": [
        "Chris Moultrie <chris@moultrie.org>",
        "Lucas Vogelsang <l@lucasvo.com>"
    ],
    "homepage": "http://github.com/steves/node-jira",
    "repository": {
        "type": "git",
        "url": "http://github.com/steves/node-jira.git"
    },
    "engine": {
        "node": ">=0.4.0"
    },
    "main": "./lib/jira.js",
    "licenses": [
        {
            "type": "The MIT License",
            "url": "http://www.opensource.org/licenses/mit-license.php"
        }
    ],
    "dependencies": {
        "request": "<2.16.0",
        "oauth": "^0.9.11"
    },
    "scripts": {
        "test": "grunt test"
    },
    "devDependencies": {
        "grunt": "^0.4.4",
        "grunt-bump": "0.0.13",
        "grunt-docco": "^0.3.3",
        "grunt-jasmine-node": "^0.2.1",
        "coffee-script": "^1.7.1",
        "grunt-jslint": "^1.1.8",
        "rewire": "^2.0.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

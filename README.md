# npmtest-sendevent

#### basic test coverage for  sendevent (v1.0.4)  [![npm package](https://img.shields.io/npm/v/npmtest-sendevent.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sendevent) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sendevent.svg)](https://travis-ci.org/npmtest/node-npmtest-sendevent)

#### Middleware for server-sent-events with iframe fallback

[![NPM](https://nodei.co/npm/sendevent.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sendevent)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sendevent/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sendevent/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sendevent/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sendevent/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sendevent/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sendevent/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sendevent/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sendevent/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sendevent/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sendevent/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sendevent/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sendevent/build/test-report.html](https://npmtest.github.io/node-npmtest-sendevent/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sendevent/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sendevent/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sendevent/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sendevent/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sendevent/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sendevent/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sendevent/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sendevent/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "sendevent",
    "version": "1.0.4",
    "description": "Middleware for server-sent-events with iframe fallback",
    "keywords": [
        "sse",
        "eventsource",
        "server-sent events",
        "comet",
        "long-polling"
    ],
    "repository": {
        "type": "git",
        "url": "http://github.com/fgnass/sendevent.git"
    },
    "main": "index.js",
    "browser": "client.js",
    "scripts": {
        "test": "mocha -g local"
    },
    "devDependencies": {
        "mocha": "~1.14.0",
        "express": "~3.4.4",
        "browserify-middleware": "~1.19.0",
        "supertest": "~0.8.1",
        "sauce-connect-launcher": "~0.2.2",
        "wd": "~0.2.5"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

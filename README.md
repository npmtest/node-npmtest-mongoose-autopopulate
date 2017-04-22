# npmtest-mongoose-autopopulate

#### basic test coverage for  [mongoose-autopopulate (v0.5.0)](https://github.com/mongodb-js/mongoose-autopopulate)  [![npm package](https://img.shields.io/npm/v/npmtest-mongoose-autopopulate.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mongoose-autopopulate) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mongoose-autopopulate.svg)](https://travis-ci.org/npmtest/node-npmtest-mongoose-autopopulate)

#### Always populate() certain fields in your mongoose schemas

[![NPM](https://nodei.co/npm/mongoose-autopopulate.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mongoose-autopopulate)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mongoose-autopopulate/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mongoose-autopopulate/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mongoose-autopopulate/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mongoose-autopopulate/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mongoose-autopopulate/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mongoose-autopopulate/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mongoose-autopopulate/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mongoose-autopopulate/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mongoose-autopopulate/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mongoose-autopopulate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mongoose-autopopulate/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mongoose-autopopulate/build/test-report.html](https://npmtest.github.io/node-npmtest-mongoose-autopopulate/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mongoose-autopopulate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mongoose-autopopulate/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mongoose-autopopulate/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mongoose-autopopulate/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mongoose-autopopulate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mongoose-autopopulate/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mongoose-autopopulate/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mongoose-autopopulate/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Valeri Karpov"
    },
    "bugs": {
        "url": "https://github.com/mongodb-js/mongoose-autopopulate/issues"
    },
    "dependencies": {},
    "description": "Always populate() certain fields in your mongoose schemas",
    "devDependencies": {
        "acquit": "0.4.1",
        "istanbul": "0.4.5",
        "mocha": "3.2.0",
        "mongoose": "4.x",
        "underscore": "1.8.3"
    },
    "directories": {},
    "dist": {
        "shasum": "c5595256c061754e146a55cd40dcbba3fc7d5abf",
        "tarball": "https://registry.npmjs.org/mongoose-autopopulate/-/mongoose-autopopulate-0.5.0.tgz"
    },
    "gitHead": "0b5d75b57221e9a89450e8f6bbad2de5d0cc5ae2",
    "homepage": "https://github.com/mongodb-js/mongoose-autopopulate",
    "keywords": [
        "mongoose",
        "populate",
        "autopopulate",
        "mongodb"
    ],
    "license": "Apache 2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "vkarpov15"
        }
    ],
    "name": "mongoose-autopopulate",
    "optionalDependencies": {},
    "peerDependencies": {
        "mongoose": "4.x"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mongodb-js/mongoose-autopopulate.git"
    },
    "scripts": {
        "test": "mocha ./test/*.js",
        "test-integration": "mocha ./test/integration.js",
        "test-travis": "istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec ./test/*"
    },
    "version": "0.5.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

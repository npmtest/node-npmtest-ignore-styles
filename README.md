# npmtest-ignore-styles

#### test coverage for  [ignore-styles (v5.0.1)](https://github.com/bkonkle/ignore-styles#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-ignore-styles.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ignore-styles) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ignore-styles.svg)](https://travis-ci.org/npmtest/node-npmtest-ignore-styles)

#### Ignore imported style files when running in Node

[![NPM](https://nodei.co/npm/ignore-styles.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ignore-styles)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ignore-styles/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ignore-styles/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ignore-styles/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ignore-styles/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ignore-styles/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ignore-styles/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ignore-styles/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ignore-styles/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ignore-styles/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ignore-styles/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ignore-styles/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ignore-styles/build/test-report.html](https://npmtest.github.io/node-npmtest-ignore-styles/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ignore-styles/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ignore-styles/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ignore-styles/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ignore-styles/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ignore-styles/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ignore-styles/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ignore-styles/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ignore-styles/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Brandon Konkle"
    },
    "bugs": {
        "url": "https://github.com/bkonkle/ignore-styles/issues"
    },
    "dependencies": {},
    "description": "Ignore imported style files when running in Node",
    "devDependencies": {
        "babel-cli": "^6.3.17",
        "babel-plugin-transform-object-assign": "^6.3.13",
        "babel-preset-es2015-loose": "^6.1.3",
        "babel-preset-react": "^6.3.13",
        "babel-register": "^6.3.13",
        "chai": "^3.4.1",
        "mocha": "^2.3.3",
        "standard": "^7.1.2"
    },
    "directories": {},
    "dist": {
        "shasum": "b49ef2274bdafcd8a4880a966bfe38d1a0bf4671",
        "tarball": "https://registry.npmjs.org/ignore-styles/-/ignore-styles-5.0.1.tgz"
    },
    "gitHead": "5673c0b72b7c79f7b94bc1f5d7f3ccea1ef82621",
    "homepage": "https://github.com/bkonkle/ignore-styles#readme",
    "keywords": [
        "webpack",
        "css",
        "testing"
    ],
    "license": "MIT",
    "main": "lib/ignore-styles.js",
    "maintainers": [
        {
            "name": "bkonkle"
        }
    ],
    "name": "ignore-styles",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/bkonkle/ignore-styles.git"
    },
    "scripts": {
        "build": "babel ignore-styles.js -s -o lib/ignore-styles.js",
        "prepublish": "npm run build",
        "test": "standard ignore-styles.js && mocha --require babel-register",
        "watch": "babel ignore-styles.js -s -o lib/ignore-styles.js -w"
    },
    "version": "5.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

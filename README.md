# test coverage for  [gulp-svg2png (v2.0.2)](https://github.com/akoenig/gulp-svg2png)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-svg2png.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-svg2png) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-svg2png.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-svg2png)
#### A gulp plugin for converting SVGs to PNGs.

[![NPM](https://nodei.co/npm/gulp-svg2png.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-svg2png)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-svg2png/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-svg2png/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-svg2png/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-svg2png/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-svg2png/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-svg2png/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-svg2png/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-svg2png/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-svg2png/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-svg2png/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-svg2png/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-svg2png/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-svg2png/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-svg2png/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-svg2png/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-svg2png/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-svg2png/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-svg2png/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-svg2png/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-svg2png/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-svg2png/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "André König"
    },
    "bugs": {
        "url": "https://github.com/akoenig/gulp-svg2png/issues"
    },
    "dependencies": {
        "gulp-util": "^3.0.7",
        "map-stream": "0.0.6",
        "map-stream-limit": "^1.1.0",
        "svg2png": "^3.0.0"
    },
    "description": "A gulp plugin for converting SVGs to PNGs.",
    "devDependencies": {
        "chai": "^3.0.0",
        "imagesize": "^1.0.0",
        "mocha": "^2.2.5",
        "typescript": "^1.7.3",
        "typings": "^0.8.1"
    },
    "directories": {},
    "dist": {
        "shasum": "dc9393802d410211e9cc56db3acf85400d929144",
        "tarball": "https://registry.npmjs.org/gulp-svg2png/-/gulp-svg2png-2.0.2.tgz"
    },
    "engines": {
        "node": "^6.0.0"
    },
    "gitHead": "a53c64fc45d73b50f4f125c3cb11305937bb5580",
    "homepage": "https://github.com/akoenig/gulp-svg2png",
    "keywords": [
        "gulpplugin",
        "svg",
        "png",
        "converter",
        "svg2png"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "akoenig"
        }
    ],
    "name": "gulp-svg2png",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/akoenig/gulp-svg2png.git"
    },
    "scripts": {
        "build": "npm i && npm run typings && npm run compile",
        "compile": "tsc",
        "mocha": "mocha ./specs/*.spec.js",
        "test": "npm run build && npm run mocha",
        "typings": "typings install -SA"
    },
    "version": "2.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

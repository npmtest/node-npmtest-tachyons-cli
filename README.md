# npmtest-tachyons-cli

#### basic test coverage for  [tachyons-cli (v1.0.11)](https://github.com/tachyons-css/tachyons-cli#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-tachyons-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-tachyons-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-tachyons-cli.svg)](https://travis-ci.org/npmtest/node-npmtest-tachyons-cli)

#### Postprocess tachyons stylesheets

[![NPM](https://nodei.co/npm/tachyons-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/tachyons-cli)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-tachyons-cli/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-tachyons-cli/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-tachyons-cli/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-tachyons-cli/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-tachyons-cli/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-tachyons-cli/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-tachyons-cli/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-tachyons-cli/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-tachyons-cli/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-tachyons-cli/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-tachyons-cli/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-tachyons-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-tachyons-cli/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-tachyons-cli/build/test-report.html](https://npmtest.github.io/node-npmtest-tachyons-cli/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-tachyons-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-tachyons-cli/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-tachyons-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-tachyons-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-tachyons-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-tachyons-cli/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-tachyons-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-tachyons-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "John Otander",
        "url": "johnotander.com"
    },
    "bin": {
        "tachyons": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/tachyons-css/tachyons-cli/issues"
    },
    "dependencies": {
        "authors-to-markdown": "^0.1.0",
        "chalk": "^1.1.3",
        "copy-files": "^0.1.0",
        "css-mqpacker": "^5.0.1",
        "cssstats": "^3.0.0-beta.2",
        "file-exists": "^2.0.0",
        "immutable-css": "^1.1.2",
        "is-blank": "^1.1.0",
        "is-present": "^1.0.0",
        "lodash": "^4.16.6",
        "meow": "^3.7.0",
        "mkdirp": "^0.5.1",
        "single-trailing-newline": "^1.0.0",
        "tachyons-build-css": "^1.1.2"
    },
    "description": "Postprocess tachyons stylesheets",
    "devDependencies": {
        "ava": "^0.16.0",
        "pify": "^2.3.0",
        "standard": "^10.0.2",
        "tachyons-type-scale": "6.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "b643443e44badc26bb7392ba55e6f7401e87b2fb",
        "tarball": "https://registry.npmjs.org/tachyons-cli/-/tachyons-cli-1.0.11.tgz"
    },
    "engines": {
        "node": ">=6"
    },
    "files": [
        "cli.js",
        "templates"
    ],
    "gitHead": "7680117ed13583a4039d404309ef057016c73af8",
    "homepage": "https://github.com/tachyons-css/tachyons-cli#readme",
    "keywords": [
        "tachyons",
        "css",
        "cli",
        "cli-app"
    ],
    "license": "ISC",
    "main": "index.js",
    "maintainers": [
        {
            "name": "donnieberg"
        },
        {
            "name": "johno"
        },
        {
            "name": "mrmrs"
        }
    ],
    "name": "tachyons-cli",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/tachyons-css/tachyons-cli.git"
    },
    "scripts": {
        "lint": "standard",
        "test": "ava -v",
        "test:rebuild": "ava -v test/regenerate-output.js"
    },
    "version": "1.0.11"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

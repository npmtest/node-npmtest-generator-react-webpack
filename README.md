# npmtest-generator-react-webpack

#### basic test coverage for  [generator-react-webpack (v3.3.4)](https://github.com/react-webpack-generators/generator-react-webpack#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-generator-react-webpack.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-generator-react-webpack) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-generator-react-webpack.svg)](https://travis-ci.org/npmtest/node-npmtest-generator-react-webpack)

#### Yeoman generator for using React with Webpack via Babel

[![NPM](https://nodei.co/npm/generator-react-webpack.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/generator-react-webpack)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-generator-react-webpack/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-react-webpack/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-generator-react-webpack/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-generator-react-webpack/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-generator-react-webpack/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-generator-react-webpack/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-generator-react-webpack/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-generator-react-webpack/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-generator-react-webpack/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-generator-react-webpack/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-generator-react-webpack/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-react-webpack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-generator-react-webpack/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-generator-react-webpack/build/test-report.html](https://npmtest.github.io/node-npmtest-generator-react-webpack/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-generator-react-webpack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-generator-react-webpack/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-generator-react-webpack/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-generator-react-webpack/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-generator-react-webpack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-generator-react-webpack/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-generator-react-webpack/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-generator-react-webpack/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Simon Bailey",
        "url": "https://github.com/newtriks"
    },
    "bugs": {
        "url": "https://github.com/react-webpack-generators/generator-react-webpack/issues"
    },
    "contributors": [
        {
            "name": "Christian Schilling",
            "url": "https://github.com/weblogixx"
        }
    ],
    "dependencies": {
        "escodegen": "^1.7.0",
        "esprima": "^2.7.0",
        "esprima-walk": "^0.1.0",
        "react-webpack-template": "^1.0.0",
        "underscore.string": "^3.2.2",
        "yeoman-generator": "^0.24.0",
        "yeoman-welcome": "^1.0.1"
    },
    "description": "Yeoman generator for using React with Webpack via Babel",
    "devDependencies": {
        "chai": "^3.2.0",
        "mocha": "^3.0.0",
        "yeoman-assert": "^2.1.1",
        "yeoman-test": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "0cb18410ea1b4c5031931211c8584848403bac3c",
        "tarball": "https://registry.npmjs.org/generator-react-webpack/-/generator-react-webpack-3.3.4.tgz"
    },
    "engines": {
        "iojs": ">=1.1.0",
        "node": ">=4.0.0"
    },
    "gitHead": "5048445c4bef992b3486b2dbe8a63702919e803e",
    "homepage": "https://github.com/react-webpack-generators/generator-react-webpack#readme",
    "keywords": [
        "yeoman-generator",
        "react",
        "reactjs",
        "webpack",
        "scaffold",
        "framework",
        "component",
        "frontend",
        "front-end",
        "app"
    ],
    "license": "MIT",
    "main": "generators/app/index.js",
    "maintainers": [
        {
            "name": "newtriks"
        },
        {
            "name": "sthzg"
        },
        {
            "name": "weblogixx"
        }
    ],
    "name": "generator-react-webpack",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/react-webpack-generators/generator-react-webpack.git"
    },
    "scripts": {
        "release:major": "npm version major && npm publish && git push --follow-tags",
        "release:minor": "npm version minor && npm publish && git push --follow-tags",
        "release:patch": "npm version patch && npm publish && git push --follow-tags",
        "test": "mocha"
    },
    "version": "3.3.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# npmtest-webpack-validator

#### test coverage for  [webpack-validator (v3.0.0)](https://github.com/js-dxtools/webpack-validator#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-webpack-validator.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-webpack-validator) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-webpack-validator.svg)](https://travis-ci.org/npmtest/node-npmtest-webpack-validator)

#### Validate your webpack config with joi

[![NPM](https://nodei.co/npm/webpack-validator.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/webpack-validator)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-webpack-validator/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-webpack-validator/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-webpack-validator/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-webpack-validator/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-webpack-validator/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-webpack-validator/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-webpack-validator/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-webpack-validator/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-webpack-validator/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-webpack-validator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-webpack-validator/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-webpack-validator/build/test-report.html](https://npmtest.github.io/node-npmtest-webpack-validator/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-webpack-validator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-webpack-validator/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-webpack-validator/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-webpack-validator/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-webpack-validator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-webpack-validator/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-webpack-validator/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-webpack-validator/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "babel": {
        "presets": [
            "es2015",
            "stage-2"
        ]
    },
    "bin": {
        "webpack-validator": "./dist/bin/webpack-validator.js"
    },
    "bugs": {
        "url": "https://github.com/js-dxtools/webpack-validator/issues"
    },
    "config": {
        "ghooks": {
            "commit-msg": "validate-commit-msg",
            "pre-commit": "npm run validate -s"
        },
        "commitizen": {
            "path": "node_modules/cz-conventional-changelog"
        }
    },
    "contributors": [
        {
            "name": "Jonathan Werner",
            "url": "http://jonathanwerner.net"
        },
        {
            "name": "Juho Vepsäläinen",
            "url": "http://survivejs.com/"
        },
        {
            "name": "Kent C. Dodds",
            "url": "http://kentcdodds.com/"
        },
        {
            "name": "Martin Schmid"
        },
        {
            "name": "Sarbbottam Bandyopadhyay"
        }
    ],
    "dependencies": {
        "basename": "0.1.2",
        "chalk": "1.1.3",
        "commander": "2.9.0",
        "common-tags": "0.1.1",
        "cross-env": "^3.1.1",
        "find-node-modules": "^1.0.1",
        "joi": "9.0.0-0",
        "lodash": "4.11.1",
        "npmlog": "2.0.3",
        "semver": "^5.3.0",
        "shelljs": "0.7.0",
        "yargs": "4.7.1"
    },
    "description": "Validate your webpack config with joi",
    "devDependencies": {
        "autoprefixer": "6.3.6",
        "babel-cli": "6.7.7",
        "babel-core": "6.7.6",
        "babel-plugin-espower": "^2.1.2",
        "babel-preset-es2015": "6.6.0",
        "babel-preset-stage-2": "6.5.0",
        "babel-register": "6.7.2",
        "brace-expansion": "1.1.3",
        "codecov": "1.0.1",
        "commitizen": "^2.7.6",
        "compression-webpack-plugin": "^0.3.2",
        "copy-webpack-plugin": "^4.0.1",
        "cz-conventional-changelog": "^1.1.5",
        "eslint": "2.8.0",
        "eslint-config-jonathanewerner": "1.0.1",
        "extract-text-webpack-plugin": "^2.1.0",
        "ghooks": "1.2.1",
        "glob": "7.0.3",
        "html-webpack-plugin": "^2.28.0",
        "mocha": "2.4.5",
        "npm-run-all": "1.8.0",
        "nyc": "6.4.0",
        "path-here": "*",
        "path-parse": "1.0.5",
        "power-assert": "1.3.1",
        "rimraf": "2.5.2",
        "semantic-release": "^4.3.5",
        "sinon": "1.17.3",
        "validate-commit-msg": "2.6.1",
        "webpack": "^1",
        "webpack-md5-hash": "^0.0.5",
        "webpack-notifier": "^1.5.0",
        "with-package": "0.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "109b72e7ee91683ac8ec6c3bf1f8afb94d5006be",
        "tarball": "https://registry.npmjs.org/webpack-validator/-/webpack-validator-3.0.0.tgz"
    },
    "eslintConfig": {
        "extends": "jonathanewerner"
    },
    "files": [
        "dist"
    ],
    "gitHead": "f0721d17bbd1c957f3d73aeb7454edbe18907f1e",
    "homepage": "https://github.com/js-dxtools/webpack-validator#readme",
    "keywords": [
        "webpack",
        "config",
        "schema",
        "validation",
        "joi"
    ],
    "license": "MIT",
    "main": "dist",
    "maintainers": [
        {
            "name": "jonathanewerner"
        },
        {
            "name": "kentcdodds"
        }
    ],
    "name": "webpack-validator",
    "nyc": {
        "exclude": [
            "**/*.test.js",
            "test/**/*.js"
        ]
    },
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/js-dxtools/webpack-validator.git"
    },
    "scripts": {
        "build": "babel --ignore *.test.js -d dist src",
        "check-coverage": "nyc check-coverage --statements 100 --branches 100 --functions 100 --lines 100",
        "commit": "git-cz",
        "cover": "cross-env NODE_ENV=test nyc --reporter=lcov --reporter=text --reporter=html mocha \"src/**/*.test.js\"",
        "lint": "eslint .",
        "prebuild": "rimraf dist",
        "report-coverage": "cat ./coverage/lcov.info | node_modules/.bin/codecov",
        "semantic-release": "semantic-release pre && npm publish && semantic-release post",
        "test": "cross-env NODE_ENV=test mocha \"src/**/*.test.js\"",
        "validate": "npm-run-all --parallel lint cover build test --sequential check-coverage",
        "watch:test": "npm run test -- -w"
    },
    "version": "3.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

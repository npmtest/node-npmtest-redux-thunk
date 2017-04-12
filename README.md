# test coverage for  [redux-thunk (v2.2.0)](https://github.com/gaearon/redux-thunk)  [![npm package](https://img.shields.io/npm/v/npmtest-redux-thunk.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-redux-thunk) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-redux-thunk.svg)](https://travis-ci.org/npmtest/node-npmtest-redux-thunk)
#### Thunk middleware for Redux.

[![NPM](https://nodei.co/npm/redux-thunk.png?downloads=true)](https://www.npmjs.com/package/redux-thunk)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-redux-thunk/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-redux-thunk/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-redux-thunk/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-redux-thunk/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-redux-thunk/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-redux-thunk/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-redux-thunk/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-redux-thunk/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-redux-thunk/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-redux-thunk/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-redux-thunk%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-redux-thunk/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-redux-thunk/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-redux-thunk%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-redux-thunk/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-redux-thunk/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-redux-thunk/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dan Abramov",
        "email": "dan.abramov@me.com"
    },
    "bugs": {
        "url": "https://github.com/gaearon/redux-thunk/issues"
    },
    "dependencies": {},
    "description": "Thunk middleware for Redux.",
    "devDependencies": {
        "babel-cli": "^6.6.5",
        "babel-core": "^6.6.5",
        "babel-eslint": "^5.0.0-beta4",
        "babel-loader": "^6.2.4",
        "babel-plugin-check-es2015-constants": "^6.6.5",
        "babel-plugin-transform-es2015-arrow-functions": "^6.5.2",
        "babel-plugin-transform-es2015-block-scoped-functions": "^6.6.5",
        "babel-plugin-transform-es2015-block-scoping": "^6.6.5",
        "babel-plugin-transform-es2015-classes": "^6.6.5",
        "babel-plugin-transform-es2015-computed-properties": "^6.6.5",
        "babel-plugin-transform-es2015-destructuring": "^6.6.5",
        "babel-plugin-transform-es2015-for-of": "^6.6.0",
        "babel-plugin-transform-es2015-function-name": "^6.5.0",
        "babel-plugin-transform-es2015-literals": "^6.5.0",
        "babel-plugin-transform-es2015-modules-commonjs": "^6.6.5",
        "babel-plugin-transform-es2015-object-super": "^6.6.5",
        "babel-plugin-transform-es2015-parameters": "^6.6.5",
        "babel-plugin-transform-es2015-shorthand-properties": "^6.5.0",
        "babel-plugin-transform-es2015-spread": "^6.6.5",
        "babel-plugin-transform-es2015-sticky-regex": "^6.5.0",
        "babel-plugin-transform-es2015-template-literals": "^6.6.5",
        "babel-plugin-transform-es2015-unicode-regex": "^6.5.0",
        "babel-plugin-transform-es3-member-expression-literals": "^6.5.0",
        "babel-plugin-transform-es3-property-literals": "^6.5.0",
        "chai": "^3.2.0",
        "cross-env": "^1.0.7",
        "eslint": "^1.10.2",
        "eslint-config-airbnb": "1.0.2",
        "eslint-plugin-react": "^4.1.0",
        "mocha": "^2.2.5",
        "redux": "^3.4.0",
        "rimraf": "^2.5.2",
        "typescript": "^1.8.10",
        "typescript-definition-tester": "0.0.4",
        "webpack": "^1.12.14"
    },
    "directories": {},
    "dist": {
        "shasum": "e615a16e16b47a19a515766133d1e3e99b7852e5",
        "tarball": "https://registry.npmjs.org/redux-thunk/-/redux-thunk-2.2.0.tgz"
    },
    "files": [
        "lib",
        "es",
        "src",
        "dist",
        "index.d.ts"
    ],
    "gitHead": "4f96ec0239453623adde857b7e7ad8c4f2897bf1",
    "homepage": "https://github.com/gaearon/redux-thunk",
    "jsnext:main": "es/index.js",
    "keywords": [
        "redux",
        "thunk",
        "middleware",
        "redux-middleware",
        "flux"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "aikoven",
            "email": "dan.lytkin@gmail.com"
        },
        {
            "name": "gaearon",
            "email": "dan.abramov@gmail.com"
        },
        {
            "name": "timdorr",
            "email": "timdorr@timdorr.com"
        }
    ],
    "name": "redux-thunk",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/gaearon/redux-thunk.git"
    },
    "scripts": {
        "build": "npm run build:commonjs && npm run build:umd && npm run build:umd:min && npm run build:es",
        "build:commonjs": "cross-env BABEL_ENV=commonjs babel src --out-dir lib",
        "build:es": "cross-env BABEL_ENV=es babel src --out-dir es",
        "build:umd": "cross-env BABEL_ENV=commonjs NODE_ENV=development webpack",
        "build:umd:min": "cross-env BABEL_ENV=commonjs NODE_ENV=production webpack",
        "clean": "rimraf lib dist es",
        "lint": "eslint src test",
        "posttest": "npm run lint",
        "prepublish": "npm run clean && npm run test && npm run build",
        "test": "cross-env BABEL_ENV=commonjs mocha --compilers js:babel-core/register --reporter spec test/*.js"
    },
    "typings": "./index.d.ts",
    "version": "2.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

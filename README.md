# api documentation for  [eslint-config-airbnb-base (v11.1.2)](https://github.com/airbnb/javascript)  [![npm package](https://img.shields.io/npm/v/npmdoc-eslint-config-airbnb-base.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-eslint-config-airbnb-base) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-eslint-config-airbnb-base.svg)](https://travis-ci.org/npmdoc/node-npmdoc-eslint-config-airbnb-base)
#### Airbnb's base JS ESLint config, following our styleguide

[![NPM](https://nodei.co/npm/eslint-config-airbnb-base.png?downloads=true)](https://www.npmjs.com/package/eslint-config-airbnb-base)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eslint-config-airbnb-base/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-eslint-config-airbnb-base_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eslint-config-airbnb-base/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-eslint-config-airbnb-base/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-eslint-config-airbnb-base/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jake Teton-Landis",
        "url": "https://twitter.com/@jitl"
    },
    "bugs": {
        "url": "https://github.com/airbnb/javascript/issues"
    },
    "contributors": [
        {
            "name": "Jake Teton-Landis",
            "url": "https://twitter.com/jitl"
        },
        {
            "name": "Jordan Harband",
            "email": "ljharb@gmail.com",
            "url": "http://ljharb.codes"
        },
        {
            "name": "Harrison Shoff",
            "url": "https://twitter.com/hshoff"
        }
    ],
    "dependencies": {},
    "description": "Airbnb's base JS ESLint config, following our styleguide",
    "devDependencies": {
        "babel-preset-airbnb": "^2.2.3",
        "babel-tape-runner": "^2.0.1",
        "editorconfig-tools": "^0.1.1",
        "eslint": "^3.18.0",
        "eslint-find-rules": "^1.14.3",
        "eslint-plugin-import": "^2.2.0",
        "in-publish": "^2.0.0",
        "safe-publish-latest": "^1.1.1",
        "tape": "^4.6.3"
    },
    "directories": {},
    "dist": {
        "shasum": "259209a7678bf693e31cbe8f953f206b6aa7ccc3",
        "tarball": "https://registry.npmjs.org/eslint-config-airbnb-base/-/eslint-config-airbnb-base-11.1.2.tgz"
    },
    "engines": {
        "node": ">= 4"
    },
    "homepage": "https://github.com/airbnb/javascript",
    "keywords": [
        "eslint",
        "eslintconfig",
        "config",
        "airbnb",
        "javascript",
        "styleguide"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "airbnb",
            "email": "jordan.harband+npm@airbnb.com"
        },
        {
            "name": "ljharb",
            "email": "ljharb@gmail.com"
        }
    ],
    "name": "eslint-config-airbnb-base",
    "optionalDependencies": {},
    "peerDependencies": {
        "eslint": "^3.18.0",
        "eslint-plugin-import": "^2.2.0"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/airbnb/javascript.git"
    },
    "scripts": {
        "lint": "eslint .",
        "prelint": "editorconfig-tools check * rules/* test/*",
        "prepublish": "(in-install || eslint-find-rules --unused) && (not-in-publish || npm test) && safe-publish-latest",
        "pretest": "npm run --silent lint",
        "test": "npm run --silent tests-only",
        "tests-only": "babel-tape-runner ./test/test-*.js",
        "travis": "npm run --silent test"
    },
    "version": "11.1.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module eslint-config-airbnb-base](#apidoc.module.eslint-config-airbnb-base)
1.  object <span class="apidocSignatureSpan">eslint-config-airbnb-base.</span>extends
1.  object <span class="apidocSignatureSpan">eslint-config-airbnb-base.</span>parserOptions
1.  object <span class="apidocSignatureSpan">eslint-config-airbnb-base.</span>rules



# <a name="apidoc.module.eslint-config-airbnb-base"></a>[module eslint-config-airbnb-base](#apidoc.module.eslint-config-airbnb-base)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

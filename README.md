# npmdoc-baffle

#### basic api documentation for  [baffle (v0.3.6)](https://camwiegert.github.io/baffle)  [![npm package](https://img.shields.io/npm/v/npmdoc-baffle.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-baffle) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-baffle.svg)](https://travis-ci.org/npmdoc/node-npmdoc-baffle)

#### A tiny javascript library for obfuscating and revealing text in DOM elements.

[![NPM](https://nodei.co/npm/baffle.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/baffle)

- [https://npmdoc.github.io/node-npmdoc-baffle/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-baffle/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-baffle/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-baffle/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-baffle/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-baffle/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Cam Wiegert"
    },
    "babel": {
        "presets": [
            "es2015"
        ],
        "plugins": [
            [
                "transform-es2015-classes",
                {
                    "loose": true
                }
            ]
        ]
    },
    "bugs": {
        "url": "https://github.com/camwiegert/baffle/issues"
    },
    "dependencies": {},
    "description": "A tiny javascript library for obfuscating and revealing text in DOM elements.",
    "devDependencies": {
        "babel-core": "^6.10.4",
        "babel-loader": "^6.2.4",
        "babel-preset-es2015": "^6.9.0",
        "eslint": "^3.1.1",
        "webpack": "^1.13.1"
    },
    "directories": {},
    "dist": {
        "shasum": "989d8a6363a19e630da85a3480422883f0bda4d0",
        "tarball": "https://registry.npmjs.org/baffle/-/baffle-0.3.6.tgz"
    },
    "eslintConfig": {
        "extends": "eslint:recommended",
        "env": {
            "browser": true,
            "node": true
        },
        "parserOptions": {
            "ecmaVersion": 6,
            "sourceType": "module"
        }
    },
    "gitHead": "aca50f26879c06de00328b0d7032c31eadee4ca3",
    "homepage": "https://camwiegert.github.io/baffle",
    "license": "MIT",
    "main": "dist/baffle.min.js",
    "maintainers": [
        {
            "name": "camwiegert"
        }
    ],
    "name": "baffle",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/camwiegert/baffle.git"
    },
    "scripts": {
        "build": "webpack -p",
        "lint": "eslint src/**/*.js",
        "start": "webpack -wp"
    },
    "version": "0.3.6",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

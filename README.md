# npmdoc-ip-address

#### api documentation for  [ip-address (v5.8.8)](https://github.com/beaugunderson/ip-address#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-ip-address.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ip-address) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ip-address.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ip-address)

#### A library for parsing IPv4 and IPv6 IP addresses in node and the browser.

[![NPM](https://nodei.co/npm/ip-address.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ip-address)

- [https://npmdoc.github.io/node-npmdoc-ip-address/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ip-address/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ip-address/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ip-address/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ip-address/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ip-address/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Beau Gunderson",
        "url": "https://beaugunderson.com/"
    },
    "bugs": {
        "url": "https://github.com/beaugunderson/ip-address/issues"
    },
    "dependencies": {
        "jsbn": "0.1.0",
        "lodash.find": "^4.6.0",
        "lodash.max": "^4.0.1",
        "lodash.merge": "^4.6.0",
        "lodash.padstart": "^4.6.1",
        "lodash.repeat": "^4.1.0",
        "sprintf-js": "^1.0.3",
        "util-deprecate": "^1.0.2"
    },
    "description": "A library for parsing IPv4 and IPv6 IP addresses in node and the browser.",
    "devDependencies": {
        "browserify": "^13.1.1",
        "chai": "^3.5.0",
        "codecov.io": "^0.1.6",
        "documentation": "^4.0.0-beta9",
        "istanbul": "^0.4.5",
        "mocha": "^3.2.0",
        "mochify": "^2.18.1"
    },
    "directories": {},
    "dist": {
        "shasum": "5fd1f8f7465249fb7d2b3c1eec7b41d29d1f1b76",
        "tarball": "https://registry.npmjs.org/ip-address/-/ip-address-5.8.8.tgz"
    },
    "engines": {
        "node": ">= 0.10"
    },
    "gitHead": "70f95e8c94192e2187d9cc694cfbd708dd647448",
    "homepage": "https://github.com/beaugunderson/ip-address#readme",
    "keywords": [
        "ipv6",
        "ipv4",
        "browser",
        "validation"
    ],
    "license": "MIT",
    "main": "ip-address.js",
    "maintainers": [
        {
            "name": "beaugunderson"
        }
    ],
    "name": "ip-address",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/beaugunderson/ip-address.git"
    },
    "scripts": {
        "docs": "documentation --github --output docs --format html ./ip-address.js",
        "prepublish": "browserify ./ip-address-globals.js > ./dist/ip-address-globals.js",
        "test": "mocha -R spec"
    },
    "version": "5.8.8",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

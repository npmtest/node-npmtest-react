# npmtest-react

#### basic test coverage for  [react (16.4.0)](https://reactjs.org/)  [![npm package](https://img.shields.io/npm/v/npmtest-react.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react.svg)](https://travis-ci.org/npmtest/node-npmtest-react)

#### React is a JavaScript library for building user interfaces.

[![NPM](https://nodei.co/npm/react.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react/tree/alpha)|
|--:|:--|
| coverage : | [![coverage](https://npmtest.github.io/node-npmtest-react/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react/build/app) || build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react/build/coverage.html/index.html)

[![coverage](https://npmtest.github.io/node-npmtest-react/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react/build/test-report.html](https://npmtest.github.io/node-npmtest-react/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react/build/screenshot.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react/build/screenshot.npmPackageDependencyTree.svg)



# package.json

```json

{
    "browserify": {
        "transform": [
            "loose-envify"
        ]
    },
    "bugs": {
        "url": "https://github.com/facebook/react/issues"
    },
    "dependencies": {
        "fbjs": "^0.8.16",
        "loose-envify": "^1.1.0",
        "object-assign": "^4.1.1",
        "prop-types": "^15.6.0"
    },
    "description": "React is a JavaScript library for building user interfaces.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "integrity": "sha512-K0UrkLXSAekf5nJu89obKUM7o2vc6MMN9LYoKnCa+c+8MJRAT120xzPLENcWSRc7GYKIg0LlgJRDorrufdglQQ==",
        "shasum": "402c2db83335336fba1962c08b98c6272617d585",
        "tarball": "https://registry.npmjs.org/react/-/react-16.4.0.tgz",
        "fileCount": 8,
        "unpackedSize": 123264,
        "npm-signature": "-----BEGIN PGP SIGNATURE-----\r\nVersion: OpenPGP.js v3.0.4\r\nComment: https://openpgpjs.org\r\n\r\nwsFcBAEBCAAQBQJbBgnXCRA9TVsSAnZWagAARQcP/A9oWqeucMVkEoWwVrRn\n9FA7yP3yPqIvpri9o9LCR5kXjdwKPEqGzFPpYE596z76O7q1NSXYWWLcc+x0\nMhwntQLRLTiBCcs1v7a8GNIZfsPnp3bhf/bo08oGhKxWqknAAA6rnCN2EOFH\nZNxc9Yxb6eqTx3SRUUEeyfeolncOSMuaNbbY6j06NsPfzrpv8G3YvrLudwLA\nuSTnRYyDYHFRC7uSdjUx4YRXYm3EI1VwgrMdkqaG3FHhoJ401YEby8AVjqSe\nHs5k1+ok7R0Zd7TjhWAQzkkkbxoGKwEXsN/WnGq08z02tEj0FQKqky1QImdo\nn6uf69HTT6inYvvMjuRPj2kss6lxYJUBvfZGuSiRDFwA/3V/lxtId6tlSUT6\n1b2zLbTusR8+Ek+ErRnWDDiYUDKN8P+P3vPc6OlocmZLqHjcBizSOsiyLfti\nHJ4yoS6zWgkGxla2Mvt2zz7sTNz8DLLsvAkAiTXQjGVx/DAnKzsA7qI08q4C\nhTiPp2qd4f+TIcZ16UeMmKRUaX342IErBrcFMgxQSD/PeYapivkV6s0WolL9\n2w5GlK2f4h4aiWwgFeN37bDq16vBWTgSpuUVR6JhMSVe+o2YPDwyt9c8n1MA\n1QmxfD3G5FQEgWcHdeO9soQGd9dzECP0jIkgVwodNHb1Edt2sVRbK//9jnqS\n87GT\r\n=Wavl\r\n-----END PGP SIGNATURE-----\r\n"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "LICENSE",
        "README.md",
        "index.js",
        "cjs/",
        "umd/"
    ],
    "homepage": "https://reactjs.org/",
    "keywords": [
        "react"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "acdlite"
        },
        {
            "name": "brianvaughn"
        },
        {
            "name": "fb"
        },
        {
            "name": "flarnie"
        },
        {
            "name": "gaearon"
        },
        {
            "name": "sophiebits"
        },
        {
            "name": "trueadm"
        }
    ],
    "name": "react",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/facebook/react.git"
    },
    "version": "2018.6.10",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

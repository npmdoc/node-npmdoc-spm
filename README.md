# npmdoc-spm

#### api documentation for  [spm (v3.9.0-beta3)](http://spmjs.io)  [![npm package](https://img.shields.io/npm/v/npmdoc-spm.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-spm) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-spm.svg)](https://travis-ci.org/npmdoc/node-npmdoc-spm)

#### Static Package Manager

[![NPM](https://nodei.co/npm/spm.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/spm)

- [https://npmdoc.github.io/node-npmdoc-spm/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-spm/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-spm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-spm/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-spm/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-spm/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "spm",
    "version": "3.9.0-beta3",
    "preferGlobal": "true",
    "description": "Static Package Manager",
    "author": "Hsiaoming Yang <me@lepture.com>",
    "homepage": "http://spmjs.io",
    "repository": {
        "type": "git",
        "url": "https://github.com/spmjs/spm.git"
    },
    "keywords": [
        "bower",
        "browser",
        "cmd",
        "command line",
        "commonjs",
        "component",
        "module",
        "npm",
        "package",
        "seajs",
        "spmjs",
        "tool"
    ],
    "dependencies": {
        "archy": "~1.0.0",
        "babel-core": "~4.7.16",
        "chokidar": "~1.0.3",
        "co": "~4.6.0",
        "colorful": "~2.1.0",
        "commander": "~2.5.0",
        "crequire": "~1.5.3",
        "debug": "^2.1.1",
        "empty-dir": "~0.1.0",
        "exeq": "~2.0.0",
        "extend": "~2.0.0",
        "father": "~1.0.0",
        "fs-extra": "~0.13.0",
        "fs-symlink": "1.1.0",
        "fstream": "~1.0.3",
        "fstream-ignore": "~1.0.2",
        "glob": "~5.0.12",
        "gulp-template": "~1.1.1",
        "inherits": "~1.0.0",
        "inquirer": "~0.8.0",
        "internal-ip": "~1.0.0",
        "istanbul": "~0.3.5",
        "istanbul-instrumenter-loader": "~0.1.2",
        "mocha-phantomjs": "3.5.6",
        "nico-spm": "~0.5.2",
        "phantomjs": "~1.9.1",
        "react-tools": "~0.12.2",
        "request": "~2.51.0",
        "rimraf": "~2.2.8",
        "scripts-hook": "~0.1.3",
        "semver": "~4.1.0",
        "sort-array": "~0.1.0",
        "spm-client": "~0.4.0",
        "spm-log": "~0.1.1",
        "spm-webpack": "~1.0.0",
        "spm-webpack-server": "~1.0.0",
        "spmrc": "~1.2.0",
        "tar": "~1.0.3",
        "test-console": "~0.7.1",
        "through2": "~2.0.0",
        "uniq": "~1.0.1",
        "vinyl-fs": "~0.3.13",
        "whoami": "~0.0.3",
        "win-spawn": "~2.0.0"
    },
    "devDependencies": {
        "coveralls": "~2.11.2",
        "gulp-unzip": "~0.1.1",
        "jshint": "*",
        "ls-archive": "~1.0.2",
        "mocha": "*",
        "muk": "~0.3.1",
        "should": "~4.3.1",
        "sinon": "~1.12.1"
    },
    "bin": {
        "spm": "bin/spm"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "scripts": {
        "test": "make test"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# api documentation for  [spm (v3.6.12)](http://spmjs.io)  [![npm package](https://img.shields.io/npm/v/npmdoc-spm.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-spm) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-spm.svg)](https://travis-ci.org/npmdoc/node-npmdoc-spm)
#### Static Package Manager

[![NPM](https://nodei.co/npm/spm.png?downloads=true)](https://www.npmjs.com/package/spm)

[![apidoc](https://npmdoc.github.io/node-npmdoc-spm/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-spm_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-spm/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-spm/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-spm/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Hsiaoming Yang",
        "email": "me@lepture.com"
    },
    "bin": {
        "spm": "bin/spm"
    },
    "bugs": {
        "url": "https://github.com/spmjs/spm/issues"
    },
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
        "gnode": "~0.1.1",
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
        "spm-webpack": "~0.7.0",
        "spm-webpack-server": "~0.7.0",
        "spmrc": "~1.2.0",
        "tar": "~1.0.3",
        "test-console": "~0.7.1",
        "through2": "~2.0.0",
        "uniq": "~1.0.1",
        "vinyl-fs": "~0.3.13",
        "whoami": "~0.0.3",
        "win-spawn": "~2.0.0"
    },
    "description": "Static Package Manager",
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
    "directories": {},
    "dist": {
        "shasum": "9fdddafaefa974cac8ad6581fe40f2c7a3d546da",
        "tarball": "https://registry.npmjs.org/spm/-/spm-3.6.12.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "4da55f553d3437ec90ac09b74922b663facfff6f",
    "homepage": "http://spmjs.io",
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
    "maintainers": [
        {
            "name": "afc163",
            "email": "afc163@gmail.com"
        },
        {
            "name": "kangpangpang",
            "email": "kangpangpang@gmail.com"
        },
        {
            "name": "lepture",
            "email": "sopheryoung@gmail.com"
        },
        {
            "name": "lifesinger",
            "email": "lifesinger@gmail.com"
        },
        {
            "name": "pigcan",
            "email": "jiangjay818@gmail.com"
        },
        {
            "name": "popomore",
            "email": "sakura9515@gmail.com"
        },
        {
            "name": "sorrycc",
            "email": "sorrycc@gmail.com"
        },
        {
            "name": "yyfrankyy",
            "email": "yyfrankyy@gmail.com"
        }
    ],
    "name": "spm",
    "optionalDependencies": {},
    "preferGlobal": "true",
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/spmjs/spm.git"
    },
    "scripts": {
        "test": "make test"
    },
    "version": "3.6.12"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module spm](#apidoc.module.spm)
1.  [function <span class="apidocSignatureSpan">spm.</span>doc (argv, callback)](#apidoc.element.spm.doc)
1.  object <span class="apidocSignatureSpan">spm.</span>client

#### [module spm.client](#apidoc.module.spm.client)
1.  [function <span class="apidocSignatureSpan">spm.client.</span>config (obj)](#apidoc.element.spm.client.config)
1.  [function <span class="apidocSignatureSpan">spm.client.</span>info ()](#apidoc.element.spm.client.info)
1.  [function <span class="apidocSignatureSpan">spm.client.</span>install ()](#apidoc.element.spm.client.install)
1.  [function <span class="apidocSignatureSpan">spm.client.</span>login ()](#apidoc.element.spm.client.login)
1.  [function <span class="apidocSignatureSpan">spm.client.</span>publish ()](#apidoc.element.spm.client.publish)
1.  [function <span class="apidocSignatureSpan">spm.client.</span>search ()](#apidoc.element.spm.client.search)
1.  [function <span class="apidocSignatureSpan">spm.client.</span>unpublish ()](#apidoc.element.spm.client.unpublish)

#### [module spm.doc](#apidoc.module.spm.doc)
1.  [function <span class="apidocSignatureSpan">spm.</span>doc (argv, callback)](#apidoc.element.spm.doc.doc)
1.  [function <span class="apidocSignatureSpan">spm.doc.</span>build (argv, callback)](#apidoc.element.spm.doc.build)
1.  [function <span class="apidocSignatureSpan">spm.doc.</span>publish (argv, callback)](#apidoc.element.spm.doc.publish)
1.  [function <span class="apidocSignatureSpan">spm.doc.</span>server (argv, callback)](#apidoc.element.spm.doc.server)



# <a name="apidoc.module.spm"></a>[module spm](#apidoc.module.spm)

#### <a name="apidoc.element.spm.doc"></a>[function <span class="apidocSignatureSpan">spm.</span>doc (argv, callback)](#apidoc.element.spm.doc)
- description and source-code
```javascript
doc = function (argv, callback) {
  callback = callback || noop;
  if (argv.clean) cleanDoc();
  if (argv.build) return build(argv, callback);
  if (argv.publish) return publish(argv, callback);
  return server(argv, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.spm.client"></a>[module spm.client](#apidoc.module.spm.client)

#### <a name="apidoc.element.spm.client.config"></a>[function <span class="apidocSignatureSpan">spm.client.</span>config (obj)](#apidoc.element.spm.client.config)
- description and source-code
```javascript
function config(obj) {
  if (!obj) {
    debug('get %j', _config);
    return _config;
  }
  copy(_config, obj);
  debug('set %j', _config);
  return _config;
}
```
- example usage
```shell
...
if (exists('package.json')) {
  var pkg = readJSON('package.json');
  var spm = pkg.spm || {};
  registry = spm.registry;
}

// load global config from spmrc
client.config({
  registry: registry || spmrc.get('registry'),
  proxy: spmrc.get('proxy'),
  auth: spmrc.get('auth'),
  temp: spmrc.get('user.temp')
});

exports.config = client.config;
...
```

#### <a name="apidoc.element.spm.client.info"></a>[function <span class="apidocSignatureSpan">spm.client.</span>info ()](#apidoc.element.spm.client.info)
- description and source-code
```javascript
function createPromise() {
  return co.call(this, fn.apply(this, arguments));
}
```
- example usage
```shell
...

  });
}

function buildPackage(opts, isWatch, callback) {
  var compiler = webpack(opts);
  compiler.plugin('compile', function() {
log.info('build', 'compile');
  });
  compiler.plugin('done', function(stats) {
printResult(stats);
log.info('build', 'done');

if (callback) {
  callback();
...
```

#### <a name="apidoc.element.spm.client.install"></a>[function <span class="apidocSignatureSpan">spm.client.</span>install ()](#apidoc.element.spm.client.install)
- description and source-code
```javascript
function createPromise() {
  return co.call(this, fn.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.spm.client.login"></a>[function <span class="apidocSignatureSpan">spm.client.</span>login ()](#apidoc.element.spm.client.login)
- description and source-code
```javascript
function createPromise() {
  return co.call(this, fn.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.spm.client.publish"></a>[function <span class="apidocSignatureSpan">spm.client.</span>publish ()](#apidoc.element.spm.client.publish)
- description and source-code
```javascript
function createPromise() {
  return co.call(this, fn.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.spm.client.search"></a>[function <span class="apidocSignatureSpan">spm.client.</span>search ()](#apidoc.element.spm.client.search)
- description and source-code
```javascript
function createPromise() {
  return co.call(this, fn.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.spm.client.unpublish"></a>[function <span class="apidocSignatureSpan">spm.client.</span>unpublish ()](#apidoc.element.spm.client.unpublish)
- description and source-code
```javascript
function createPromise() {
  return co.call(this, fn.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.spm.doc"></a>[module spm.doc](#apidoc.module.spm.doc)

#### <a name="apidoc.element.spm.doc.doc"></a>[function <span class="apidocSignatureSpan">spm.</span>doc (argv, callback)](#apidoc.element.spm.doc.doc)
- description and source-code
```javascript
doc = function (argv, callback) {
  callback = callback || noop;
  if (argv.clean) cleanDoc();
  if (argv.build) return build(argv, callback);
  if (argv.publish) return publish(argv, callback);
  return server(argv, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.spm.doc.build"></a>[function <span class="apidocSignatureSpan">spm.doc.</span>build (argv, callback)](#apidoc.element.spm.doc.build)
- description and source-code
```javascript
function build(argv, callback) {
  argv.watch = false;
  argv.config = getThemePath();
  webpackWrap(argv, function() {
    nico.build(argv);
    callback();
  });
}
```
- example usage
```shell
...
module.exports.server = server;
module.exports.publish = publish;

function build(argv, callback) {
argv.watch = false;
argv.config = getThemePath();
webpackWrap(argv, function() {
  nico.build(argv);
  callback();
});
}

function server(argv, callback) {
argv.watch = true;
webpackWrap(argv, function() {
...
```

#### <a name="apidoc.element.spm.doc.publish"></a>[function <span class="apidocSignatureSpan">spm.doc.</span>publish (argv, callback)](#apidoc.element.spm.doc.publish)
- description and source-code
```javascript
function publish(argv, callback) {
  build(argv, function() {
    var pkg = readJSON('package.json');
    var registry;
    if (pkg && pkg.spm) {
      registry = pkg.spm.registry;
    }
    upload({
      doc: DOC_PATH,
      registry: argv.registry || registry
    }, callback);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.spm.doc.server"></a>[function <span class="apidocSignatureSpan">spm.doc.</span>server (argv, callback)](#apidoc.element.spm.doc.server)
- description and source-code
```javascript
function server(argv, callback) {
  argv.watch = true;
  webpackWrap(argv, function() {
    nico.server(argv, callback);
  });
}
```
- example usage
```shell
...
  callback();
});
}

function server(argv, callback) {
argv.watch = true;
webpackWrap(argv, function() {
  nico.server(argv, callback);
});
}

function webpackWrap(argv, callback) {
argv.config = getThemePath();
argv.port = argv.port || 8000;
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

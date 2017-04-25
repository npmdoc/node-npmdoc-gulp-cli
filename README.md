# npmdoc-gulp-cli

#### basic api documentation for  [gulp-cli (v1.3.0)](http://gulpjs.com)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-cli.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-cli)

#### Command line interface for gulp

[![NPM](https://nodei.co/npm/gulp-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-cli)

- [https://npmdoc.github.io/node-npmdoc-gulp-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-cli/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Gulp Team",
        "url": "http://gulpjs.com/"
    },
    "bin": {
        "gulp": "bin/gulp.js"
    },
    "bugs": {
        "url": "https://github.com/gulpjs/gulp-cli/issues"
    },
    "contributors": [],
    "dependencies": {
        "archy": "^1.0.0",
        "chalk": "^1.1.0",
        "copy-props": "^1.4.1",
        "fancy-log": "^1.1.0",
        "gulplog": "^1.0.0",
        "interpret": "^1.0.0",
        "liftoff": "^2.3.0",
        "lodash.isfunction": "^3.0.8",
        "lodash.isplainobject": "^4.0.4",
        "lodash.sortby": "^4.5.0",
        "matchdep": "^1.0.0",
        "mute-stdout": "^1.0.0",
        "pretty-hrtime": "^1.0.0",
        "semver-greatest-satisfied-range": "^1.0.0",
        "tildify": "^1.0.0",
        "v8flags": "^2.0.9",
        "wreck": "^6.3.0",
        "yargs": "^3.28.0"
    },
    "description": "Command line interface for gulp",
    "devDependencies": {
        "babel-preset-es2015": "^6.5.0",
        "babel-register": "^6.5.1",
        "coveralls": "^2.7.0",
        "eslint": "^1.7.3",
        "eslint-config-gulp": "^2.0.0",
        "expect": "^1.20.2",
        "fs-extra": "^0.26.1",
        "github-changes": "^1.0.1",
        "gulp": "github:gulpjs/gulp#4.0",
        "gulp-test-tools": "^0.6.1",
        "jscs": "^2.3.5",
        "jscs-preset-gulp": "^1.0.0",
        "marked-man": "^0.1.3",
        "mocha": "^3.2.0",
        "nyc": "^10.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "a6bfbb8be35341be290ae45cd3e401071216edd4",
        "tarball": "https://registry.npmjs.org/gulp-cli/-/gulp-cli-1.3.0.tgz"
    },
    "engines": {
        "node": ">= 0.10"
    },
    "files": [
        "index.js",
        "lib",
        "bin",
        "completion",
        "gulp.1"
    ],
    "gitHead": "879c5643a498fb485cb683b285145bd8f1ff1213",
    "homepage": "http://gulpjs.com",
    "keywords": [
        "build",
        "stream",
        "system",
        "make",
        "tool",
        "asset",
        "pipeline"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "contra"
        },
        {
            "name": "fractal"
        },
        {
            "name": "phated"
        }
    ],
    "man": [
        "gulp.1"
    ],
    "name": "gulp-cli",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/gulpjs/gulp-cli.git"
    },
    "scripts": {
        "changelog": "github-changes -o gulpjs -r gulp-cli -b master -f ./CHANGELOG.md --order-semver --use-commit-body",
        "cover": "nyc --reporter=lcov --reporter=text-summary npm test",
        "coveralls": "nyc --reporter=text-lcov npm test | coveralls",
        "lint": "eslint . && jscs index.js bin/ lib/ test/",
        "prepublish": "marked-man --name gulp docs/CLI.md > gulp.1",
        "pretest": "npm run lint",
        "test": "mocha --async-only --timeout 3000 test/lib test"
    },
    "version": "1.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

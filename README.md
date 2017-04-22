# npmtest-player

#### basic test coverage for  player (v0.6.1)  [![npm package](https://img.shields.io/npm/v/npmtest-player.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-player) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-player.svg)](https://travis-ci.org/npmtest/node-npmtest-player)

#### a command line player, supports play mp3 both from url and local stream.

[![NPM](https://nodei.co/npm/player.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/player)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-player/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-player/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-player/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-player/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-player/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-player/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-player/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-player/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-player/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-player/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-player/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-player/build/test-report.html](https://npmtest.github.io/node-npmtest-player/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-player/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-player/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-player/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-player/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-player/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-player/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-player/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-player/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "player",
    "version": "0.6.1",
    "description": "a command line player, supports play mp3 both from url and local stream.",
    "main": "dist/player.js",
    "bin": "bin/cli",
    "scripts": {
        "build": "node_modules/.bin/babel libs --out-dir dist --source-maps",
        "build-watch": "node_modules/.bin/babel libs --out-dir dist --source-maps --watch",
        "example-add": "DEBUG=player,player:* node examples/add.js",
        "example-shuffle": "DEBUG=player,player:* node examples/shuffle.js",
        "example-local": "DEBUG=player,player:* node examples/local.js",
        "example-stop": "DEBUG=player,player:* node examples/stop.js",
        "example-stop-at-last": "DEBUG=player,player:* node examples/stop-at-last.js",
        "example-playlist": "DEBUG=player,player:* node examples/playlist.js",
        "example-online": "DEBUG=player,player:* node examples/online.js",
        "example-online-proxy": "DEBUG=player,player:* node examples/online-proxy.js",
        "example-next": "DEBUG=player,player:* node examples/next.js",
        "example-metadata": "DEBUG=player,player:* node examples/metadata.js",
        "example-stream": "DEBUG=player,player:* node examples/stream.js 2>/dev/null"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/turingou/player.git"
    },
    "keywords": [
        "mp3",
        "cli",
        "audio",
        "player",
        "cli player"
    ],
    "author": "turing <o.u.turing@gmail.com>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/turingou/player/issues"
    },
    "files": [
        "bin",
        "libs",
        "dist",
        "README.md",
        "package.json"
    ],
    "dependencies": {
        "async": "^0.9.0",
        "follow-redirects": "0.0.7",
        "home": "^0.1.3",
        "keypress": "^0.2.1",
        "lame": "^1.2.2",
        "pcm-volume": "^1.0.0",
        "pool_stream": "0.0.2",
        "speaker": "^0.2.6",
        "underscore": "~1.6.0"
    },
    "devDependencies": {
        "babel": "^5.2.17",
        "debug": "^2.1.0",
        "musicmetadata": "1.0.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

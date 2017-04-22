# npmtest-react-player

#### basic test coverage for  [react-player (v0.15.0)](https://github.com/CookPete/react-player)  [![npm package](https://img.shields.io/npm/v/npmtest-react-player.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-player) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-player.svg)](https://travis-ci.org/npmtest/node-npmtest-react-player)

#### A react component for playing a variety of URLs, including file paths, YouTube, SoundCloud, Streamable, Vidme, Vimeo and Wistia

[![NPM](https://nodei.co/npm/react-player.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-player)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-player/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-player/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-player/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-player/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-player/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-player/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-player/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-player/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-player/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-player/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-player/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-player/build/test-report.html](https://npmtest.github.io/node-npmtest-react-player/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-player/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-player/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-player/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-player/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-player/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-player/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-player/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-player/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Pete Cook",
        "url": "http://github.com/cookpete"
    },
    "bugs": {
        "url": "https://github.com/CookPete/react-player/issues"
    },
    "dependencies": {
        "fetch-jsonp": "^1.0.2",
        "load-script": "^1.0.0",
        "prop-types": "^15.5.6",
        "query-string": "^4.2.3"
    },
    "description": "A react component for playing a variety of URLs, including file paths, YouTube, SoundCloud, Streamable, Vidme, Vimeo and Wistia",
    "devDependencies": {
        "auto-changelog": "^0.3.1",
        "babel-cli": "^6.16.0",
        "babel-core": "^6.16.0",
        "babel-eslint": "^7.0.0",
        "babel-loader": "^6.2.5",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-plugin-transform-es3-member-expression-literals": "^6.8.0",
        "babel-plugin-transform-es3-property-literals": "^6.8.0",
        "babel-preset-es2015": "^6.16.0",
        "babel-preset-react": "^6.16.0",
        "babel-preset-react-hmre": "^1.1.1",
        "babel-preset-stage-0": "^6.16.0",
        "chai": "^3.5.0",
        "cross-env": "^4.0.0",
        "css-loader": "^0.28.0",
        "es6-promise": "^4.0.3",
        "exports-loader": "^0.6.3",
        "express": "^4.14.0",
        "extract-text-webpack-plugin": "^2.0.0-rc.3",
        "json-loader": "^0.5.4",
        "karma": "^1.3.0",
        "karma-chai": "^0.1.0",
        "karma-chrome-launcher": "^2.0.0",
        "karma-cli": "^1.0.1",
        "karma-firefox-launcher": "^1.0.0",
        "karma-mocha": "^1.2.0",
        "karma-mocha-reporter": "^2.2.0",
        "karma-sourcemap-loader": "^0.3.7",
        "karma-webpack": "^2.0.2",
        "mocha": "^3.1.0",
        "node-sass": "^4.1.1",
        "normalize.css": "^6.0.0",
        "react": "^15.3.2",
        "react-dom": "^15.3.2",
        "rimraf": "^2.5.4",
        "sass-loader": "^6.0.1",
        "screenfull": "^3.0.2",
        "snazzy": "^7.0.0",
        "standard": "^10.0.0",
        "style-loader": "^0.16.1",
        "webpack": "^2.2.1",
        "webpack-dev-middleware": "^1.8.3",
        "webpack-hot-middleware": "^2.12.2",
        "whatwg-fetch": "^2.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "ce76415132ecd17c44e5495c5b558faba233107c",
        "tarball": "https://registry.npmjs.org/react-player/-/react-player-0.15.0.tgz"
    },
    "gitHead": "b188f6e9856bfe069717eef7f81bc67553791462",
    "homepage": "https://github.com/CookPete/react-player",
    "keywords": [
        "react",
        "media",
        "player",
        "video",
        "audio",
        "youtube",
        "soundcloud",
        "streamable",
        "vimeo",
        "wistia",
        "react-component"
    ],
    "license": "CC0-1.0",
    "main": "lib/ReactPlayer.js",
    "maintainers": [
        {
            "name": "cookpete"
        }
    ],
    "name": "react-player",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "*"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/CookPete/react-player.git"
    },
    "scripts": {
        "build:browser": "cross-env NODE_ENV=production webpack --config webpack.config.browser.js",
        "build:compile": "cross-env NODE_ENV=production babel src -d lib --ignore src/demo",
        "build:demo": "npm run clean && npm run build:webpack && cp index.html demo",
        "build:webpack": "cross-env NODE_ENV=production webpack --config webpack.config.prod.js",
        "clean": "rimraf lib demo",
        "lint": "standard --verbose | snazzy",
        "postpublish": "npm run clean",
        "prepublish": "npm run build:compile && npm run build:browser",
        "preversion": "npm run lint",
        "start": "node server.js",
        "test": "karma start test/karma.config.js",
        "update-changelog": "auto-changelog --package --template compact",
        "version": "npm run update-changelog && npm run build:browser && git add CHANGELOG.md dist"
    },
    "standard": {
        "parser": "babel-eslint",
        "ignore": [
            "/dist/*"
        ]
    },
    "typings": "index.d.ts",
    "version": "0.15.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

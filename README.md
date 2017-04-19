# npmdoc-react-sparklines

#### api documentation for  [react-sparklines (v1.6.0)](https://github.com/borisyankov/react-sparklines#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-sparklines.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-sparklines) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-sparklines.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-sparklines)

#### Beautiful and expressive Sparklines component for React

[![NPM](https://nodei.co/npm/react-sparklines.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-sparklines)

- [https://npmdoc.github.io/node-npmdoc-react-sparklines/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-sparklines/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-sparklines/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-sparklines/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-sparklines/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-sparklines/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Boris Yankov",
        "url": "https://github.com/borisyankov"
    },
    "bugs": {
        "url": "https://github.com/borisyankov/react-sparklines/issues"
    },
    "dependencies": {
        "react-addons-shallow-compare": "^15.0.2"
    },
    "description": "Beautiful and expressive Sparklines component for React ",
    "devDependencies": {
        "babel": "^6.5.2",
        "babel-core": "^6.8.0",
        "babel-loader": "^6.2.4",
        "babel-plugin-transform-object-assign": "^6.8.0",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-1": "^6.5.0",
        "babel-runtime": "^6.6.1",
        "chai": "^3.5.0",
        "enzyme": "^2.2.0",
        "hiff": "^0.3.0",
        "line-by-line": "^0.1.4",
        "mocha": "^2.4.5",
        "react": "^15.0.2",
        "react-addons-test-utils": "^15.0.2",
        "react-dom": "^15.0.2",
        "react-element-to-jsx-string": "=2.6.1",
        "replaceall": "^0.1.6",
        "webpack": "^2.1.0-beta.4",
        "webpack-dev-server": "^2.0.0-beta"
    },
    "directories": {
        "src": "src/"
    },
    "dist": {
        "shasum": "0fe5987b1895301ce724c40d78ab9a26e8a9c2bf",
        "tarball": "https://registry.npmjs.org/react-sparklines/-/react-sparklines-1.6.0.tgz"
    },
    "gitHead": "eb4ec4c20e07abbf53446da8104cce1ffeaec307",
    "homepage": "https://github.com/borisyankov/react-sparklines#readme",
    "keywords": [
        "react",
        "component",
        "react-component",
        "charts",
        "sparklines",
        "visualization",
        "jsx"
    ],
    "license": "MIT",
    "main": "build/index.js",
    "maintainers": [
        {
            "name": "borisyankov"
        }
    ],
    "name": "react-sparklines",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "*",
        "react-dom": "*"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/borisyankov/react-sparklines.git"
    },
    "scripts": {
        "compile": "webpack",
        "prepublish": "npm run compile",
        "start": "cd demo && webpack-dev-server --progress",
        "test": "mocha --compilers js:babel-core/register __tests__",
        "test:bootstrap": "node -r babel-core/register bootstrap-tests.js",
        "test:watch": "mocha --compilers js:babel-core/register --watch __tests__"
    },
    "version": "1.6.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

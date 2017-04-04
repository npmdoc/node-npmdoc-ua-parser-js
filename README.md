# api documentation for  [ua-parser-js (v0.7.12)](http://github.com/faisalman/ua-parser-js)  [![npm package](https://img.shields.io/npm/v/npmdoc-ua-parser-js.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ua-parser-js) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ua-parser-js.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ua-parser-js)
#### Lightweight JavaScript-based user-agent string parser

[![NPM](https://nodei.co/npm/ua-parser-js.png?downloads=true)](https://www.npmjs.com/package/ua-parser-js)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ua-parser-js/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-ua-parser-js_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ua-parser-js/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ua-parser-js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ua-parser-js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Faisal Salman",
        "email": "fyzlman@gmail.com",
        "url": "http://faisalman.com"
    },
    "bugs": {
        "url": "https://github.com/faisalman/ua-parser-js/issues"
    },
    "contributors": [
        {
            "name": "Faisal Salman",
            "email": "fyzlman@gmail.com"
        },
        {
            "name": "Benjamin Bertrand",
            "email": "bertrand.design@gmail.com"
        },
        {
            "name": "Carl C Von Lewin",
            "email": "carlchristianlewin@gmail.com"
        },
        {
            "name": "Christopher De Cairos",
            "email": "chris.decairos@gmail.com"
        },
        {
            "name": "Davit Barbakadze",
            "email": "jayarjo@gmail.com"
        },
        {
            "name": "Dmitry Tyschenko",
            "email": "dtyschenko@gmail.com"
        },
        {
            "name": "Douglas Li",
            "email": "doug@knotch.it"
        },
        {
            "name": "Dumitru Uzun",
            "email": "contact@duzun.me"
        },
        {
            "name": "Erik Hesselink",
            "email": "hesselink@gmail.com"
        },
        {
            "name": "Fabian Becker",
            "email": "halfdan@xnorfz.de"
        },
        {
            "name": "Hendrik Helwich",
            "email": "h.helwich@iplabs.de"
        },
        {
            "name": "Jackpoll",
            "email": "jackpoll123456@gmail.com"
        },
        {
            "name": "Jake Mc",
            "email": "startswithaj@users.noreply.github.com"
        },
        {
            "name": "John Tantalo",
            "email": "john.tantalo@gmail.com"
        },
        {
            "name": "John Yanarella",
            "email": "jmy@codecatalyst.com"
        },
        {
            "name": "Jon Buckley",
            "email": "jon@jbuckley.ca"
        },
        {
            "name": "Kendall Buchanan",
            "email": "kendall@kendagriff.com"
        },
        {
            "name": "Lee Treveil",
            "email": "leetreveil@gmail.com"
        },
        {
            "name": "Leonardo",
            "email": "leofiore@libero.it"
        },
        {
            "name": "Max Maurer",
            "email": "maxemanuel.maurer@gmail.com"
        },
        {
            "name": "Michael Hess",
            "email": "mhess@connectify.me"
        },
        {
            "name": "OtakuSiD",
            "email": "otakusid@gmail.com"
        },
        {
            "name": "Ross Noble",
            "email": "rosshnoble@gmail.com"
        },
        {
            "name": "Sandro Sonntag",
            "email": "sandro.sonntag@adorsys.de"
        }
    ],
    "dependencies": {},
    "description": "Lightweight JavaScript-based user-agent string parser",
    "devDependencies": {
        "jshint": "~1.1.0",
        "mocha": "~1.8.0",
        "requirejs": "^2.3.2",
        "uglify-js": "~1.3.4",
        "verup": "^1.3.x"
    },
    "directories": {
        "dist": "dist",
        "src": "src",
        "test": "test"
    },
    "dist": {
        "shasum": "04c81a99bdd5dc52263ea29d24c6bf8d4818a4bb",
        "tarball": "https://registry.npmjs.org/ua-parser-js/-/ua-parser-js-0.7.12.tgz"
    },
    "engines": {
        "node": "*"
    },
    "gitHead": "01ae611dfa2d2c2ec3dba79c454538c0ed92e54f",
    "homepage": "http://github.com/faisalman/ua-parser-js",
    "keywords": [
        "user-agent",
        "parser",
        "browser",
        "engine",
        "os",
        "device",
        "cpu"
    ],
    "license": "(GPL-2.0 OR MIT)",
    "main": "src/ua-parser.js",
    "maintainers": [
        {
            "name": "faisalman",
            "email": "fyzlman@gmail.com"
        }
    ],
    "name": "ua-parser-js",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/faisalman/ua-parser-js.git"
    },
    "scripts": {
        "build": "uglifyjs src/ua-parser.js > dist/ua-parser.min.js --comments '/UAParser\\.js/' && uglifyjs src/ua-parser.js > dist/ua-parser.pack.js --comments '/UAParser\\.js/' --compress --mangle",
        "test": "jshint src/ua-parser.js && mocha -R nyan test/test.js",
        "version": "node ./node_modules/verup 0",
        "verup": "node ./node_modules/verup"
    },
    "title": "UAParser.js",
    "version": "0.7.12",
    "verup": {
        "files": [
            "ua-parser-js.jquery.json",
            "component.json",
            "bower.json",
            "package.js",
            "src/ua-parser.js"
        ],
        "regs": [
            "^((?:\\$|(\\s*\\*\\s*@)|(\\s*(?:var|,)?\\s+))(?:LIBVERSION|version)[\\s\\:='\"]+)([0-9]+(?:\\.[0-9]+){2,2})",
            "^(\\s?\\*.*v)([0-9]+(?:\\.[0-9]+){2,2})"
        ]
    }
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module ua-parser-js](#apidoc.module.ua-parser-js)
1.  [function <span class="apidocSignatureSpan">ua-parser-js.</span>UAParser (uastring, extensions)](#apidoc.element.ua-parser-js.UAParser)
1.  object <span class="apidocSignatureSpan">ua-parser-js.</span>BROWSER
1.  object <span class="apidocSignatureSpan">ua-parser-js.</span>CPU
1.  object <span class="apidocSignatureSpan">ua-parser-js.</span>DEVICE
1.  object <span class="apidocSignatureSpan">ua-parser-js.</span>ENGINE
1.  object <span class="apidocSignatureSpan">ua-parser-js.</span>OS
1.  string <span class="apidocSignatureSpan">ua-parser-js.</span>VERSION



# <a name="apidoc.module.ua-parser-js"></a>[module ua-parser-js](#apidoc.module.ua-parser-js)

#### <a name="apidoc.element.ua-parser-js.UAParser"></a>[function <span class="apidocSignatureSpan">ua-parser-js.</span>UAParser (uastring, extensions)](#apidoc.element.ua-parser-js.UAParser)
- description and source-code
```javascript
UAParser = function (uastring, extensions) {

    if (!(this instanceof UAParser)) {
        return new UAParser(uastring, extensions).getResult();
    }

    var ua = uastring || ((window && window.navigator && window.navigator.userAgent) ? window.navigator.userAgent : EMPTY);
    var rgxmap = extensions ? util.extend(regexes, extensions) : regexes;

    this.getBrowser = function () {
        var browser = mapper.rgx.apply(this, rgxmap.browser);
        browser.major = util.major(browser.version);
        return browser;
    };
    this.getCPU = function () {
        return mapper.rgx.apply(this, rgxmap.cpu);
    };
    this.getDevice = function () {
        return mapper.rgx.apply(this, rgxmap.device);
    };
    this.getEngine = function () {
        return mapper.rgx.apply(this, rgxmap.engine);
    };
    this.getOS = function () {
        return mapper.rgx.apply(this, rgxmap.os);
    };
    this.getResult = function() {
        return {
            ua      : this.getUA(),
            browser : this.getBrowser(),
            engine  : this.getEngine(),
            os      : this.getOS(),
            device  : this.getDevice(),
            cpu     : this.getCPU()
        };
    };
    this.getUA = function () {
        return ua;
    };
    this.setUA = function (uastring) {
        ua = uastring;
        return this;
    };
    return this;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

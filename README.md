# api documentation for  [nodeadmin (v0.1.2)](http://nodeadmin.github.io/nodeadmin)  [![npm package](https://img.shields.io/npm/v/npmdoc-nodeadmin.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-nodeadmin) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-nodeadmin.svg)](https://travis-ci.org/npmdoc/node-npmdoc-nodeadmin)
#### A fantastically elegant interface for MySQL and Node.js/Express management

[![NPM](https://nodei.co/npm/nodeadmin.png?downloads=true)](https://www.npmjs.com/package/nodeadmin)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nodeadmin/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-nodeadmin_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nodeadmin/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-nodeadmin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-nodeadmin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/nodeadmin/nodeadmin/issues"
    },
    "contributors": [
        {
            "name": "Alex Hutchison",
            "url": "https://github.com/dutchers"
        },
        {
            "name": "Andrew Nickell",
            "url": "https://github.com/nickell-andrew"
        },
        {
            "name": "Laura Knight",
            "url": "https://github.com/ljknight"
        },
        {
            "name": "Taylor Lehman",
            "url": "https://github.com/taylorleh"
        }
    ],
    "dependencies": {
        "bluebird": "^2.10.2",
        "body-parser": "^1.14.1",
        "express": "^4.13.3",
        "jsonwebtoken": "^5.4.0",
        "morgan": "^1.6.1",
        "mysql": "^2.9.0",
        "path": "^0.12.7",
        "promise-mysql": "^1.1.1",
        "randomstring": "^1.1.3",
        "socket.io": "^1.3.7"
    },
    "description": "A fantastically elegant interface for MySQL and Node.js/Express management",
    "devDependencies": {
        "chai": "^3.4.0",
        "gulp": "^3.9.0",
        "gulp-concat": "^2.6.0",
        "gulp-rename": "^1.2.2",
        "gulp-uglify": "^1.4.2",
        "mocha": "^2.3.3",
        "supertest": "^1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "ca73c1b9105aadaa557508d21a0f7a49b3971eb0",
        "tarball": "https://registry.npmjs.org/nodeadmin/-/nodeadmin-0.1.2.tgz"
    },
    "gitHead": "53a4839af784044b26cdc862083f8fe934cd462f",
    "homepage": "http://nodeadmin.github.io/nodeadmin",
    "keywords": [
        "express",
        "mysql",
        "middleware",
        "admin",
        "server admin",
        "databases",
        "dashboard"
    ],
    "license": "MIT",
    "main": "middleware/index.js",
    "maintainers": [
        {
            "name": "ahutch",
            "email": "ahutch006@gmail.com"
        },
        {
            "name": "ljknight",
            "email": "ljknight@gmail.com"
        },
        {
            "name": "nickell-andrew",
            "email": "nickell.andrew@gmail.com"
        },
        {
            "name": "taylorleh",
            "email": "taylorlehman111@gmail.com"
        }
    ],
    "name": "nodeadmin",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/nodeadmin/nodeadmin.git"
    },
    "scripts": {
        "postinstall": "npm install --prefix ./middleware/public/",
        "test": "node ./middleware/tests/test.js"
    },
    "version": "0.1.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module nodeadmin](#apidoc.module.nodeadmin)



# <a name="apidoc.module.nodeadmin"></a>[module nodeadmin](#apidoc.module.nodeadmin)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

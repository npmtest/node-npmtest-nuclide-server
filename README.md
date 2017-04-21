# npmtest-nuclide-server

#### basic test coverage for  nuclide-server (v0.0.35)  [![npm package](https://img.shields.io/npm/v/npmtest-nuclide-server.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nuclide-server) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nuclide-server.svg)](https://travis-ci.org/npmtest/node-npmtest-nuclide-server)

#### Provides a collection of services that are run on the Nuclide server to support remote file editing

[![NPM](https://nodei.co/npm/nuclide-server.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nuclide-server)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nuclide-server/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nuclide-server/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nuclide-server/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nuclide-server/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nuclide-server/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nuclide-server/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nuclide-server/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-nuclide-server/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-nuclide-server/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nuclide-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-nuclide-server/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-nuclide-server/build/test-report.html](https://npmtest.github.io/node-npmtest-nuclide-server/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-nuclide-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nuclide-server/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-nuclide-server/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nuclide-server/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nuclide-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nuclide-server/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nuclide-server/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nuclide-server/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "nuclide-start-server": "./nuclide-start-server"
    },
    "dependencies": {
        "connect": "3.3.4",
        "event-kit": "1.1.1",
        "fs-plus": "2.8.1",
        "mv": "2.1.1",
        "nuclide-analytics": "0.0.35",
        "nuclide-arcanist-base": "0.0.35",
        "nuclide-buck-base": "0.0.35",
        "nuclide-clang": "0.0.35",
        "nuclide-commons": "0.0.35",
        "nuclide-debugger-hhvm-proxy": "0.0.35",
        "nuclide-filewatcher-base": "0.0.35",
        "nuclide-flow-base": "0.0.35",
        "nuclide-fuzzy-file-search-service": "0.0.35",
        "nuclide-hack-base": "0.0.35",
        "nuclide-hack-search-service": "0.0.35",
        "nuclide-hg-repository-base": "0.0.35",
        "nuclide-logging": "0.0.35",
        "nuclide-node-transpiler": "0.0.35",
        "nuclide-ocaml-base": "0.0.35",
        "nuclide-path-search": "0.0.35",
        "nuclide-remote-search": "0.0.35",
        "nuclide-remote-uri": "0.0.35",
        "nuclide-service-parser": "0.0.35",
        "nuclide-service-transformer": "0.0.35",
        "nuclide-source-control-helpers": "0.0.35",
        "nuclide-test-helpers": "0.0.35",
        "nuclide-version": "0.0.35",
        "request": "2.60.0",
        "rx": "3.1.1",
        "temp": "0.8.3",
        "uuid": "2.0.1",
        "ws": "0.7.1",
        "yargs": "3.1.0"
    },
    "description": "Provides a collection of services that are run on the Nuclide server to support remote file editing",
    "devDependencies": {
        "nuclide-jasmine": "0.0.35",
        "rimraf": "2.2.8"
    },
    "license": "SEE LICENSE IN LICENSE",
    "name": "nuclide-server",
    "nuclide": {
        "customDeps": "fb/package.json",
        "customServices": "fb/custom-services-config.json",
        "packageType": "Node",
        "testRunner": "npm",
        "testsCannotBeRunInParallel": true
    },
    "repository": "https://github.com/facebook/nuclide",
    "scripts": {
        "test": "node --harmony node_modules/.bin/jasmine-node-transpiled spec"
    },
    "version": "0.0.35"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

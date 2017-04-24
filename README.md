# modern-node-boilerplate
Minimal, general purpose NodeJS boilerplate

[![CircleCI](https://circleci.com/gh/longseespace/modern-node-boilerplate.svg?style=svg)](https://circleci.com/gh/longseespace/modern-node-boilerplate)
[![Airbnb-js-style](https://img.shields.io/badge/code%20style-airbnb-brightgreen.svg)](https://github.com/airbnb/javascript)

Getting Started
---------------

Clone the repo and install the necessary node modules:
```shell
$ git clone https://github.com/longseespace/modern-node-boilerplate.git
$ cd modern-node-boilerplate
$ yarn install
$ yarn run dev
```

Command line cheat sheet:

|`yarn run...`|Description|
|---|---|
|`start`|Builds and runs main index script (`index.js`)|
|`dev`|Runs main script (`index.js`). Nodemon will be enabled in development.|
|`build`|Compiles the application to disk (`~/dist` by default).|
|`test`|Runs unit tests with jest and generates a coverage report.|
|`test:watch`|Runs jest and watches for changes to re-run tests; does not generate coverage reports.|
|`lint`|Lint all `.js` files.|
|`lint:fix`|Lint and fix all `.js` files. [Read more on this](http://eslint.org/docs/user-guide/command-line-interface.html#fix).|

Testing
-------

To add a unit test, simply create a `.test.js` file anywhere in `~/src`.
Coverage reports will be compiled to `~/coverage` by default.

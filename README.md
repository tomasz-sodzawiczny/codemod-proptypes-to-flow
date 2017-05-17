# codemod-proptypes-to-flow [![Build Status](https://travis-ci.org/billyvg/codemod-proptypes-to-flow.svg?branch=master)](https://travis-ci.org/billyvg/codemod-proptypes-to-flow) [![codecov](https://codecov.io/gh/billyvg/codemod-proptypes-to-flow/branch/master/graph/badge.svg)](https://codecov.io/gh/billyvg/codemod-proptypes-to-flow)

Removes `React.PropTypes` and attempts to transform to [Flow](http://flow.org/).

### Setup & Run
  * `npm install -g jscodeshift`
  * `git clone https://github.com/billyvg/codemod-proptypes-to-flow`
  * `jscodeshift -t codemod-proptypes-to-flow/src/index.js <path>`
  * Use the `-d` option for a dry-run and use `-p` to print the output
    for comparison

### Not working/Implemented yet
  * Custom validators
  * `React.createClass`
  * Use of importing PropTypes

### Contributors
  * Thanks to [@skovhus](https://github.com/skovhus) for adding support for functional components and modernizing the codebase a bit (a lot)

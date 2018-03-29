[![Build Status](https://travis-ci.org/ConsenSys/solidity-parser.svg?branch=master)](https://travis-ci.org/ConsenSys/solidity-parser)

## [consensys/solidity-parser](https://github.com/ConsenSys/solidity-parser) with project specific grammar rules
Branches of this repo contain parsers that can interpret solidity files of <branch name> allowing you to run
code analysis on contracts that use custom pre-processsing to deploy or run their tests.


### Branches


**Gnosis**: 
  + Uses interpolation, e.g. `{{Variable}}` to defer address assignments to contract Contructors until
  the contracts execution context is known.


### License

MIT

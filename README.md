# FlightSurety

FlightSurety is a sample application project for Udacity's Blockchain course.

## Install

This repository contains Smart Contract code in Solidity (using Truffle), tests (also using Truffle), dApp scaffolding (using HTML, CSS and JS) and server app scaffolding.

To install, download or clone the repo, then:

`npm install`
`truffle compile`

## Develop Client

To run truffle tests:

`truffle test ./test/flightSurety.js`
`truffle test ./test/oracles.js`

To use the dapp:

`truffle migrate`
`npm run dapp`

To view dapp:

`http://localhost:8000`

## Develop Server

`npm run server`
`truffle test ./test/oracles.js`

## Deploy

To build dapp for prod:
`npm run dapp:prod`

Deploy the contents of the ./dapp folder


## Resources

* [How does Ethereum work anyway?](https://medium.com/@preethikasireddy/how-does-ethereum-work-anyway-22d1df506369)
* [BIP39 Mnemonic Generator](https://iancoleman.io/bip39/)
* [Truffle Framework](http://truffleframework.com/)
* [Ganache Local Blockchain](http://truffleframework.com/ganache/)
* [Remix Solidity IDE](https://remix.ethereum.org/)
* [Solidity Language Reference](http://solidity.readthedocs.io/en/v0.4.24/)
* [Ethereum Blockchain Explorer](https://etherscan.io/)
* [Web3Js Reference](https://github.com/ethereum/wiki/wiki/JavaScript-API)


## env config

no


### dependencies

truffle env

```
$ truffle version
Truffle v5.7.0 (core: 5.7.0)
Ganache v7.5.0
Solidity - ^0.8.17 (solc-js)
Node v16.19.0
Web3.js v1.7.4
```

node_modules

```
$ npm outdated
Package                     Current  Wanted  Latest  Location                                 Depended by
@truffle/hdwallet-provider    1.7.0   1.7.0   2.1.3  node_modules/@truffle/hdwallet-provider  FlightSurety
babel-loader                  8.0.5   8.0.5   9.1.0  node_modules/babel-loader                FlightSurety
bignumber.js                  8.0.2   8.0.2   9.1.1  node_modules/bignumber.js                FlightSurety
css-loader                    1.0.1   1.0.1   6.7.3  node_modules/css-loader                  FlightSurety
express                      4.16.4  4.16.4  4.18.2  node_modules/express                     FlightSurety
file-loader                   3.0.1   3.0.1   6.2.0  node_modules/file-loader                 FlightSurety
html-loader                   0.5.5   0.5.5   4.2.0  node_modules/html-loader                 FlightSurety
html-webpack-plugin           3.2.0   3.2.0   5.5.0  node_modules/html-webpack-plugin         FlightSurety
openzeppelin-solidity         4.0.0   4.6.0   4.6.0  node_modules/openzeppelin-solidity       FlightSurety
style-loader                 0.23.1  0.23.1   3.3.1  node_modules/style-loader                FlightSurety
superstatic                   6.0.3   6.0.3   9.0.0  node_modules/superstatic                 FlightSurety
web3                          1.7.4   1.7.4   1.8.1  node_modules/web3                        FlightSurety
webpack                      4.46.0  4.46.0  5.75.0  node_modules/webpack                     FlightSurety
webpack-cli                  3.3.12  3.3.12   5.0.1  node_modules/webpack-cli                 FlightSurety
webpack-dev-server           3.11.0  3.11.3  4.11.1  node_modules/webpack-dev-server          FlightSurety
webpack-node-externals        1.7.2   1.7.2   3.0.0  node_modules/webpack-node-externals      FlightSurety
```

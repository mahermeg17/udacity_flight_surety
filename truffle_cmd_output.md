~/Projects/udacity/FlightSurety$ truffle migrate --reset
Warning: Both truffle-config.js and truffle.js were found. Using truffle-config.js.

Compiling your contracts...
===========================
> Everything is up to date, there is nothing to compile.
Warning: Both truffle-config.js and truffle.js were found. Using truffle-config.js.


Starting migrations...
======================
> Network name:    'development'
> Network id:      1672179564169
> Block gas limit: 6721975 (0x6691b7)


1_initial_migration.js
======================
⠦ Fetching solc version list from solc-bin. Attempt #1
   Deploying 'Migrations'
   ----------------------
   > transaction hash:    0x765bf5270929395977bde1f43d78186afc23d97451066b3d8f72209a103cb5f1
   > Blocks: 0            Seconds: 0
   > contract address:    0x8CdaF0CD259887258Bc13a92C0a6dA92698644C0
   > block number:        1
   > block timestamp:     1672179571
   > account:             0x627306090abaB3A6e1400e9345bC60c78a8BEf57
   > balance:             99.99549526
   > gas used:            225237 (0x36fd5)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.00450474 ETH

   > Saving migration to chain.om solc-bin. Attempt #1
   > Saving artifacts to chain.
   -------------------------------------
   > Total cost:          0.00450474 ETH


2_deploy_contracts.js
=====================
⠹ Fetching solc version list from solc-bin. Attempt #1
   Deploying 'FlightSuretyData'
   ----------------------------
   > transaction hash:    0xd080245d88798e4f74b7be27e57c02580da8b4d0e2f2a93f194bc77c9216c4ee
   > Blocks: 0            Seconds: 0
   > contract address:    0x345cA3e014Aaf5dcA488057592ee47305D9B3e10
   > block number:        3
   > block timestamp:     1672179571
   > account:             0x627306090abaB3A6e1400e9345bC60c78a8BEf57
   > balance:             99.95230572
   > gas used:            2117114 (0x204dfa)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.04234228 ETH

⠼ Fetching solc version list from solc-bin. Attempt #1
   Deploying 'FlightSuretyApp'
   ---------------------------
   > transaction hash:    0x251a8678dcdb2e54eb6008429be9b3edc0a535637ce340bf59ad27d88fd05ec5
   > Blocks: 0            Seconds: 0
   > contract address:    0xf25186B5081Ff5cE73482AD761DB0eB0d25abfBF
   > block number:        4
   > block timestamp:     1672179571
   > account:             0x627306090abaB3A6e1400e9345bC60c78a8BEf57
   > balance:             99.90518272
   > gas used:            2356150 (0x23f3b6)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.047123 ETH

   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:          0.08946528 ETH

Summary
=======
> Total deployments:   3
> Final cost:          0.09397002 ETH

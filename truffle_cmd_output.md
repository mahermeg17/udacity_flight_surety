$truffle migrate --reset

Compiling your contracts...
===========================
> Everything is up to date, there is nothing to compile.
⠦ Fetching solc version list from solc-bin. Attempt #1
⠧ Fetching solc version list from solc-bin. Attempt #1
Starting migrations...
======================
> Network name:    'development'
> Network id:      1671452651695
> Block gas limit: 6721975 (0x6691b7)


1_initial_migration.js
======================
⠏ Fetching solc version list from solc-bin. Attempt #1
   Deploying 'Migrations'
   ----------------------
   > transaction hash:    0x4567d97a7fd3bce2e52fdea1f6318f692e2686a2574169ed40a379f6142b39d1
   > Blocks: 0            Seconds: 0
   > contract address:    0x8CdaF0CD259887258Bc13a92C0a6dA92698644C0
   > block number:        1
   > block timestamp:     1671452666
   > account:             0x627306090abaB3A6e1400e9345bC60c78a8BEf57
   > balance:             99.99454424
   > gas used:            272788 (0x42994)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.00545576 ETH

   > Saving migration to chain.om solc-bin. Attempt #1
   > Saving artifacts to chain.
   -------------------------------------
   > Total cost:          0.00545576 ETH


2_deploy_contracts.js
=====================
⠼ Fetching solc version list from solc-bin. Attempt #1
   Deploying 'FlightSuretyData'
   ----------------------------
   > transaction hash:    0x054428effbd9b9e29512239bcb5e8be36a5be9d70acf099c2be8007f18d091c9
   > Blocks: 0            Seconds: 0
   > contract address:    0x345cA3e014Aaf5dcA488057592ee47305D9B3e10
   > block number:        3
   > block timestamp:     1671452667
   > account:             0x627306090abaB3A6e1400e9345bC60c78a8BEf57
   > balance:             99.98857628
   > gas used:            255863 (0x3e777)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.00511726 ETH

⠧ Fetching solc version list from solc-bin. Attempt #1
   Deploying 'FlightSuretyApp'
   ---------------------------
   > transaction hash:    0xb396bbc8aa87a9d250a0c495ba831be2b94bc675677a9af9aeaec38a9cd8c00b
   > Blocks: 0            Seconds: 0
   > contract address:    0xf25186B5081Ff5cE73482AD761DB0eB0d25abfBF
   > block number:        4
   > block timestamp:     1671452667
   > account:             0x627306090abaB3A6e1400e9345bC60c78a8BEf57
   > balance:             99.96216074
   > gas used:            1320777 (0x142749)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.02641554 ETH

   > Saving migration to chain.om solc-bin. Attempt #1
   > Saving artifacts to chain.
   -------------------------------------
   > Total cost:           0.0315328 ETH

Summary
=======
> Total deployments:   3
> Final cost:          0.03698856 ETH

-------------------------------------------------------------------------------

$ truffle test ./test/flightSurety.js 
Using network 'development'.


Compiling your contracts...
===========================
> Everything is up to date, there is nothing to compile.
⠏ Fetching solc version list from solc-bin. Attempt #1

  Contract: Flight Surety Testsom solc-bin. Attempt #1
    1) "before all" hook: setup contract for "(multiparty) has correct initial isOperational() value"


  0 passing (366ms)
  1 failing

  1) Contract: Flight Surety Tests
       "before all" hook: setup contract for "(multiparty) has correct initial isOperational() value":
     TypeError: config.flightSuretyData.authorizeCaller is not a function
      at Context.<anonymous> (test/flightSurety.js:10:35)
      at processTicksAndRejections (node:internal/process/task_queues:96:5)

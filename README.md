# Split-or-Steal-Game

DAPP Game on ethereum blockchain deployed at [Rinkeby](https://rinkeby.etherscan.io/address/0x2ac77fe38e7be6f3d15f797594aa8d03d8810cea#code).

[How to Play](http://showmeyourcode.github.io/Split-or-Steal-Game/#about)

![DAPP Game on ethereum blockchain](https://imgur.com/Nd8nmnV.jpg)

**How to run tests**

_Prerequisite_

Download and run [Ganache](http://truffleframework.com/ganache/)

**USING REMIX**

* Open [remix(v0.4.21)](http://remix.ethereum.org/#optimize=false&version=soljson-v0.4.21+commit.dfe3193c.js)
* Copy Paste [contract](https://github.com/showmeyourcode/Split-or-Steal-Game/blob/master/truffle/contracts/SplitStealContractV2.sol) in remix IDE
* Go to _Run_ tab and in _Environment_ select _Web3 Provider_
* Provide endpoint as http://localhost:7545 (That's where Ganache is running)
* In _Run_ tab under _Accounts_ you should see a lot of accounts with some ether.
* Select any account and hit **Create** at bottom.
* Now you should see all the methods listed.
* Just go ahead and play the game by hitting appropriate method in game play.
* Do not forget to mention _Value_ in wei/ether while hitting a payble contract method.

**USING Truffle**

* Go to truffle folder

```shell
cd truffle
```

* Compile

```shell
truffle compile
```

* Migrate

```shell
truffle migrate --reset
```

* Open truffle console

```shell
truffle console
```

* Run Tests

```shell
>exec <PATH TO TEST>/TestStartRegistration.js
```

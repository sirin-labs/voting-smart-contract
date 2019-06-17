
# SIRIN LABS' Token Holders Yes\No Voting Contract

Please see below Sirin Labs smart contracts' for the [Smart Contract ][sirinlabs].

![SirinLabs Logo](images/logo.png)

## Overview
SIRIN LABS management want to all SRN stack holders (~20,000) will part of the vision, for this we create a simple smart contract with Yes\No Question that upload to the [Ethereum][ethereum] network  the stake holders can be participate and help us to build together the near feature for sirin labs

All the data will be calculated by a simple script (Link TDB)

## How To Vote
The voting procedure is very simple to the average [Ethereum][ethereum] user, by the following steps:
*  Enter one of the Ethereum wallets ([Finney][sirinlabs], [myetherwallet][myetherwallet], etc)
* Send 0 ether to the voting contract address (TBD) with data
	* Vote Yes - 0x90cf581c
	* Vote No - 0x41c12a70
* Send the transaction to blockchain network

## Contracts

Please see the [SirinVoiting.sol](SirinVoiting.sol) file.

#### Voting Functions

**voteYes**
```cs
function voteYes() public
```

**votNo**
```cs
function voteNo() public
```

#### Voting Events


**votedYesEvent**
```cs
event votedYesEvent(address voter);
```

**votedNoEvent**
```cs
event votedNoEvent(address voter);
```

## Collaborators

* **[Yossi Gruner](https://github.com/yossigruner)**
* **[Lior David](https://github.com/liordavid)**


## License

Apache License v2.0


[sirinlabs]: https://www.sirinlabs.com
[ethereum]: https://www.ethereum.org/
[myetherwallet]:(https://www.myetherwallet.com/)

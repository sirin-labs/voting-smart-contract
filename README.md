# SIRIN LABS' Voting Smart Contract

Please see below Sirin Labs smart contracts' for the [Smart Contract ][sirinlabs].

![SirinLabs Logo](images/logo.png)

## Overview
SIRIN LABS - the developer of SOLARIN, the ultra-secure smartphone - is holding a crowdsale event. Funds raised	will	support	the	development	of	FINNEY,	the	first	open	source	smartphone	and	all-in-one	PC built for the blockchain era. Customers will be able to purchase all SIRIN LABS products (SOLARIN and FINNEY) with SIRIN LABS token, the SRN.

## Contracts

Please see the [contracts/](contracts) directory.

#### Voting Functions

**deposit**
```cs
function deposit(address investor, uint256 tokensAmount) onlyOwner public payable
```
Adds Investor tokens and ETH to the vault.

**close**
```cs
function close() onlyOwner public
```
Closes the refunds, all ETH is transfered to Sirin ETH wallet.
After this function is called investors cannot refund their ETH anymore but can claim their tokens.

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

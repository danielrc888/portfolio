# Deployed ERC-20 Token

<div align="center" data-full-width="false">

<figure><img src="../../.gitbook/assets/cryptocurrency-3423264_640.webp" alt="erc-20"><figcaption></figcaption></figure>

</div>

#### Technologies

`Solidity` `Hardhat` `Ethereum` `Sepolia Testnet` `OpenZeppelin` `ERC-20`

#### Description

Token that uses OpenZeppelin ERC-20 Standard deployed on Sepolia Testnet using Hardhat.&#x20;

```solidity
//SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";

contract DanielToken is ERC20 {
    uint constant _initial_supply = 100 * (10**18);
    constructor() ERC20("Daniel", "DJRC") {
        _mint(msg.sender, _initial_supply);
    }
}
```

#### Deployment

<figure><img src="../../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

**Token contract:** [0x5e8ff3c347c71f5ddab980dbcd36cc06e10e8a11](https://sepolia.etherscan.io/address/0x5e8ff3c347c71f5ddab980dbcd36cc06e10e8a11) on Sepolia ETH Testnet

**Token name:** Daniel

**Token symbol:** DJRC

Check the source code on github

#### Resources

[OpenZeppelin ERC-20 Standard](https://docs.openzeppelin.com/contracts/3.x/erc20)

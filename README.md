# SafeVault Alpha Base on Buffer

> Create a Contract Vault to collect money and let members withdraw their share

Learn more here: https://buffer2.moneypipe.xyz

![buffer.png](buffer.png)

---

# Contract

Stream is a [minimal proxy contract](https://eips.ethereum.org/EIPS/eip-1167), which makes deployments affordable ($2 ~ $3 as of September 2022).

This repository is made up of 2 main files:

1. [Buffer.sol](contracts/Buffer2.sol): The core "Buffer" contract that handles realtime money split handling
2. [Factory.sol](contracts/Factory.sol): The factory that clones and deploys the core Stream contract

> There's an additional Test unit [TestERC20.sol](contracts/TestERC20.sol),it's just for testing purpose and is not included in the deployment.

# TODO

SafeVault beta will further introduce Timer Recover and NFT Authority guardian modules

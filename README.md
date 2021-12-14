[course TOC, code, and resources](https://github.com/smartcontractkit/full-blockchain-solidity-course-py/blob/main/README.md#lesson-7-smartcontract-lottery)

## ERC20 Token

- start OurToken.sol by copying from [Zeppelin ERC 20](https://docs.openzeppelin.com/contracts/4.x/erc20)
- [ERC20.sol (v4.2)](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v4.2/contracts/token/ERC20/ERC20.sol)
- specify openzeppelin dependency and remapping (check [github](https://github.com/OpenZeppelin/openzeppelin-contracts) for latest version)

## Scripts

- **init**.py
- 1_deploy_token.py
- helpful_scripts.py

## brownie-config

- `dotenv: .env`
- `wallets: from_key: ${PRIVATE_KEY}`

## deploy

- to Ganache: `$brownie run scripts/1_deploy_token.py`
- to Rinkeby: `$ brownie run scripts/1_deploy_token.py --network rinkeby`

**Commit 1**

## MetaMask, import token

- to add above 1000 OT token to our MetaMask, just copy and paste the contract address (0x0860C493Af7f36443FC8D2435cfE79E26aDB8E8A) from Rinkeby etherscan

## Uniswap

- we can even sell this on [uniswap](https://app.uniswap.org/#/swap)
  -> Pool -> More -> Create a pool

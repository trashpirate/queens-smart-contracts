# FLAMELNG QUEENS SMART CONTRACTS

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg?style=for-the-badge)
![Forge](https://img.shields.io/badge/forge-v0.2.0-blue.svg?style=for-the-badge)
![Solc](https://img.shields.io/badge/solc-v0.8.20-blue.svg?style=for-the-badge)
[![License: MIT](https://img.shields.io/github/license/trashpirate/queens-smart-contracts.svg?style=for-the-badge)](https://github.com/trashpirate/queens-smart-contracts/blob/master/LICENSE)

[![Website: nadinaoates.com](https://img.shields.io/badge/Portfolio-00e0a7?style=for-the-badge&logo=Website)](https://nadinaoates.com)
[![LinkedIn: nadinaoates](https://img.shields.io/badge/LinkedIn-0a66c2?style=for-the-badge&logo=LinkedIn&logoColor=f5f5f5)](https://linkedin.com/in/nadinaoates)
[![Twitter: 0xTrashPirate](https://img.shields.io/badge/@0xTrashPirate-black?style=for-the-badge&logo=X)](https://twitter.com/0xTrashPirate)

Main Repository: [https://github.com/trashpirate/flameling-queens](https://github.com/trashpirate/flameling-queens)

Project Link: [https://0x52.buyholdearn.com/](https://0x52.buyholdearn.com/)

## About
This repo includes a pseudo-randomized cross-chain NFT contract (ERC721A) using Chainlink CCIP. The contracts are deployed on BNB Testnet and Base Sepolia.

## Installation

### Install dependencies
```bash
$ make install
```

## Usage
Before running any commands, create a .env file and add the following environment variables. These are configured for BNB and BASE chain:
```bash

# network configs
RPC_LOCALHOST="http://127.0.0.1:8545"

# binance smart chain
RPC_BSC_MAIN=<rpc url>
RPC_BSC_TEST=<rpc url>
BSCSCAN_KEY=<api key>

# base chain
RPC_BASE_MAIN=<rpc url>
RPC_BASE_SEPOLIA=<rpc url>

BASESCAN_KEY=<api key>
BASESCAN_SEPOLIA_KEY=<api key>

```

### Run tests
```bash
$ forge test
```

### Deploy contract

**Testnet Payment Token**  
```bash
$ make deploy-token-testnet
```
**Testnet Source Minter**  
```bash
$ make deploy-source-testnet
```
**Testnet Destination Minter and NFT Contract**  
```bash
$ make deploy-destination-testnet
```

## Deployments

### Testnet
Payment Token:
https://testnet.bscscan.com/address/0x563f5a7fa101dd7051853604ec63103ab6226c7b

Source Minter:
https://testnet.bscscan.com/address/0xdcdf94053c9fcfe5bb7525c060b47bbc6d166ce3

Destination Minter:
https://base-sepolia.blockscout.com/address/0xCD8946Dda83af26E817579A40587efeC05aeC45B

NFT Contract:
https://base-sepolia.blockscout.com/address/0x1d4880a45e8D1B7627728b31B2D5c23Dd9DbE46b

### Mainnet
Payment Token:
https://bscscan.com/token/0x45e26B10Ae6f95d9d5133720937693E17171F7F9

Source Minter:
https://bscscan.com/address/0xf2538a2387e0ecd939377b1d7caf8cb9240bd01a

Destination Minter:
https://basescan.org/address/0x798c190062edd8b1be9a1ffe02f10212e8d5e7da

NFT Contract:
https://basescan.org/address/0x897cf93cef78f8dddff41962cd63cf030dff81c8

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Author

👤 **Nadina Oates**

* Website: [nadinaoates.com](https://nadinaoates.com)
* Twitter: [@0xTrashpirate](https://twitter.com/0xTrashpirate)
* Github: [@trashpirate](https://github.com/trashpirate)
* LinkedIn: [@nadinaoates](https://linkedin.com/in/nadinaoates)


## 📝 License

Copyright © 2024 [Nadina Oates](https://github.com/trashpirate).

This project is [MIT](https://github.com/trashpirate/queens-smart-contracts/blob/master/LICENSE) licensed.




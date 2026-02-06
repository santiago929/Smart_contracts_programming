This project was initially developed to meet the requirements of an academic assignment. However, it has since been extended and refined to make the implementation more realistic. Please note that this code snippet is provided strictly for academic demonstration purposes and has only been tested using Hardhat v2.

The smart contract allows project owners to list multiple projects and initiate crowdfunding campaigns for each one. Users can participate in these campaigns by interacting directly with the smart contract, for example by sending funds. The smart contract features:

- Time-bound fundraising campaigns.
- Minimum contribution thresholds.
- Funding goals.
- Refunds for failed projects.
- Owner withdrawals for successful projects.
- ERC-721 NFT standard reward for contributors. 
https://docs.openzeppelin.com/contracts/5.x/api/token/erc721
- Fully tested with Hardhat, Mocha and Chai.

# Project structure.

crowdfunding/
├── contracts/
│   └── CrowdFunding.sol
├── test/
│   └── CrowdFunding.test.js
├── hardhat.config.js
├── package.json
└── README.md






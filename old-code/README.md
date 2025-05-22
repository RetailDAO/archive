# Old Code

This subfolder in the [archive](https://github.com/RetailDAO/archive) repository stores deprecated code from RetailDAO’s early development, ensuring transparency and auditability. RetailDAO is a decentralized autonomous organization (DAO) on the Base Network, empowering retail investors through community governance and collective wisdom using the $RETAIL token for governance and incentives.

## Purpose
The `old-code` subfolder preserves historical code, including early smart contracts, website versions, and scripts, for reference and community review. This supports RetailDAO’s commitment to transparency by documenting the evolution of our technical infrastructure.

## Contents
### Retail DAO Genesis Proposal
The Genesis Proposal refers to the initial setup of RetailDAO, including the deployment of the $RETAIL token and the Original Mint Authorized DAO. Key details:
- **Original Mint Authorized DAO**: Deployed to manage the mint of the initial supply of 1 billion tokens.
  - **Contract Address**: [0xcbFaabb2b87E858717a52216439276956dc1C9eC](https://basescan.org/address/0xcbFaabb2b87E858717a52216439276956dc1C9eC).
  - **Files**: ([`Original DAO`](https://github.com/RetailDAO/smart-contracts/tree/main/original-dao))
  - **Status**: Deprecated; minting permissions revoked for transparency. See [smart-contracts/retail-token](https://github.com/RetailDAO/smart-contracts/tree/main/retail-token) for the details.

### Other Archived Code

- **Website v1**: Early Framer template simple website deployed, see [website](https://github.com/RetailDAO/website) repository for more details.
  - **Status**: Live online at (https://retaildao.xyz) open to feature upgrades/iterations.
- **Snapshot Scripts**: Early scripts for Snapshot off-chain proposals.
  - **File**: `-TBD-`
  - **Status**: Moved to [smart-contracts/snapshots](https://github.com/RetailDAO/smart-contracts/tree/main/snapshots).

## Transparency
- All smart contracts are verified on [BaseScan](https://basescan.org/) to address common DEX scanners warning flags.
- The $RETAIL token’s minting permissions is going to be revoked to ensure a fixed supply, documented in [smart-contracts/original-dao](https://github.com/RetailDAO/smart-contracts/tree/main/original-dao).
- Historical code is preserved here for community review and auditability.

## Current Implementations
Active code is maintained in:
- [smart-contracts](https://github.com/RetailDAO/smart-contracts): Current $RETAIL token, DAO, and multisig contracts.
- [website](https://github.com/RetailDAO/website): Latest website code.
- [documentation](https://github.com/RetailDAO/documentation): Detailed guides and contract addresses.

## Contributing
To review or propose updates to archived code, open an issue or pull request in this repository. See [documentation/docs/community/CONTRIBUTING.md](https://github.com/RetailDAO/documentation/blob/main/docs/community/CONTRIBUTING.md) for guidelines.

## Contact
Questions? Reach out on [Discord](https://discord.gg/mpABdUQXJC) or open an issue in this repository.
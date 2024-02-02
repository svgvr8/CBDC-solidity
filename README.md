# Custom CBDC, Creator & Administrator

This project demonstrates the implementation of a custom Central Bank Digital Currency (CBDC) using the ERC20 token standard on Ethereum, enhanced with administrative controls. The contract includes features like custom token creation, admin-controlled transfers, and the ability to approve or disapprove delegates for token management.

The project includes:

# A custom ERC20 token contract (CBDC.sol) with administrative functionalities.
- Tests for the contract to ensure correct behavior of the token creation, transfer, approval, and disapproval processes.
- A deployment script (deploy.js) to deploy the contract to an Ethereum network.

# Available Functionality
- Creation of a custom ERC20 token with specified name, symbol, and decimals.
- Administrative control over token transfers.
- Ability to approve or disapprove addresses for token transfer on behalf of the token owner.
- Transfer of ownership of the token contract to a new admin.

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```

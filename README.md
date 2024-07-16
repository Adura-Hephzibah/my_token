# MyToken DApp

This DApp allows users to transfer ERC-20 tokens between accounts on the Ethereum blockchain. It includes functionality to connect a wallet, check balances, and transfer tokens.

## Prerequisites

- MetaMask installed in your browser.
- Node.js and npm installed on your machine.
- An Ethereum test network (e.g., Rinkeby or Ropsten).
- Access Remix IDE on [here](remix.ethereum.org)
- Visual studio code


## Usage

Follow this instructions to install and interact with this DApp

- Clone this repository using
  `git clone https://github.com/Adura-Hephzibah/my_token.git `
  This is the front-end interface of the DApp

- Install metamask wallet browser extension on your browser and create a wallet and create 2 addresses for the interaction.

- Open [Remix IDE](https://remix.ethereum.org/), Create a new file named `MyToken.sol` and copy the code from the local MyToken.sol file in the reposiroty to it.

- Click on the "Solidity Compiler" tab on the left sidebar. Select the appropriate compiler version (0.8.x). Click "Compile MyToken.sol".

- Deploy the contract while under injected Provider-metamask . Ensure your metamask wallet is open and connected on the Linea Sepolia test net.

- After deployment, the contract will show on your Remix IDE.

- Copy the deployed contract address and update the `contractAddress` and `contractABI` in app.js. This would enable interaction from the front-end

- Use the deployed contract's UI in Remix to test transfer, balanceOf, approve, and transferFrom functions.

- Use the front-end to interact with the DApp to transfer between the two accounts and to see the corresponding balances.
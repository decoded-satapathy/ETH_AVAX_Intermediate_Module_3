# LinuxEduToken

This Solidity program is an ERC20 token contract named "LinuxEduToken". It demonstrates the use of the OpenZeppelin library for creating a burnable ERC20 token with ownership capabilities. The purpose of this program is to serve as a starting point for those who are new to Solidity and want to get a feel for how to implement basic ERC20 token functionalities.

## Demo Video 
[Video Explanation](https://www.loom.com/share/91d2d8edc44749f99d576bde635a3c87)

## Description

This program is a smart contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contract, "LinuxEduToken", extends the functionality of OpenZeppelin's ERC20 and Ownable contracts. It includes functions for minting new tokens, burning tokens, and transferring tokens. This program serves as an introduction to more complex Solidity programming using OpenZeppelin's libraries and can be used as a foundation for more advanced token contracts in the future.

## Getting Started

### Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, follow these steps:

1. **Create a New File**:
   - Click on the "+" icon in the left-hand sidebar.
   - Save the file with a `.sol` extension (e.g., `LinuxEduToken.sol`).

2. **Copy and Paste the Code**:
   - Copy and paste the code present in the `LinuxEduToken.sol` file into the new file you created on Remix.

3. **Compile the Code**:
   - Click on the "Solidity Compiler" tab in the left-hand sidebar.
   - Ensure the "Compiler" option is set to "0.8.20" (or another compatible version).
   - Click on the "Compile LinuxEduToken.sol" button.

4. **Deploy the Contract**:
   - Click on the "Deploy & Run Transactions" tab in the left-hand sidebar.
   - Select the "LinuxEduToken" contract from the dropdown menu.
   - Enter the initial supply (e.g., `1000000`) in the deployment input box.
   - Click on the "Deploy" button.

5. **Interact with the Contract**:
   - After deployment, you can interact with the contract using the provided functions.
   - To mint tokens, call the `mintToken` function with the recipient address and amount.
   - To burn tokens, call the `burnToken` function with the amount to burn.
   - To transfer tokens, call the `transferToken` function with the recipient address and amount.

## Authors

Metacrafter Om Satapathy  
[@OmSatapathy4](https://twitter.com/OmSatapathy4)

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

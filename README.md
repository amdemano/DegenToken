# DegenToken

DegenToken is an ERC20 token with additional functionalities such as minting, burning, and a gacha system. This token is intended for use within the Degen Gaming ecosystem.

## Description

The `DegenToken` contract extends the OpenZeppelin ERC20 and Ownable contracts. It allows the owner to mint new tokens, any holder to burn their tokens, and includes a gacha system where users can spend tokens to try their luck at obtaining different characters.

## Getting Started

### Installing

You can interact with this contract using Remix, a popular web-based Solidity development environment.

1. Open [Remix](https://remix.ethereum.org/)
2. Create a new file and copy the contents of `DegenToken.sol` into the file.
3. Ensure you have the OpenZeppelin contracts available. You can import them directly in Remix.

### Executing program

To deploy and interact with the contract, follow these steps in Remix:

1. **Compile the contract**:
    - Open the "Solidity Compiler" tab.
    - Select the appropriate compiler version (e.g., 0.8.18).
    - Click "Compile DegenToken.sol".

2. **Deploy the contract**:
    - Open the "Deploy & Run Transactions" tab.
    - Select the environment (e.g., JavaScript VM, Injected Web3 for MetaMask).
    - Click "Deploy".

3. **Interact with the contract**:
    - Use the deployed contract instance in the "Deployed Contracts" section.
    - Call functions such as `mint`, `burn`, `transfer`, and `gacha`.

## Help

If you encounter any issues or have questions, feel free to open an issue in the GitHub repository.

## Authors

Ashley Demano

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

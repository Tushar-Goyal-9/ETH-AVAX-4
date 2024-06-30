# DegenGamingToken ERC20 Contract

This Solidity program implements the DegenGamingToken ERC20 token contract, showcasing functionalities such as minting, burning, transferring tokens, redeeming tokens for in-game items, and setting item costs. It serves as an example of implementing an ERC20 token with additional features on the Ethereum blockchain, specifically designed for a gaming platform.

## Description

DegenGamingToken is a smart contract written in Solidity for Ethereum and compatible networks like Avalanche. It includes the following functionalities:

- **Token Information:**
  - Name: Degen Gaming Token
  - Symbol: DGT
  - Decimals: 18 (default for ERC20)
  - Initial Supply: 1,000,000 tokens minted to the contract creator

- **Functions:**
  - **Constructor:** Upon deployment, mints 1,000,000 tokens to the contract creator.
  - **Minting:** Allows the owner to mint additional tokens.
  - **Burning:** Enables token holders to burn (destroy) their own tokens.
  - **Transferring:** Standard ERC20 transfer function.
  - **Balance Check:** Standard ERC20 balance check function.
  - **Redeeming:** Allows players to redeem tokens for items in the in-game store.
  - **Setting Item Cost:** Allows the owner to set the cost of items in tokens.

## Executing the Program

### Deployment and Interaction:

To deploy and interact with the DegenGamingToken contract:

1. **Using Remix IDE:**
   - Go to [Remix Ethereum IDE](https://remix.ethereum.org/).
   - Create a new file named `DegenGamingToken.sol` and paste the contract code.
   - Compile the contract in the "Solidity Compiler" tab.

2. **Deployment:**
   - Deploy the contract in the "Deploy & Run Transactions" tab.
   - Select `DegenGamingToken` from the contract dropdown and click "Deploy".

3. **Token Operations:**
   - Upon deployment, the deployer receives 1,000,000 Degen Gaming Tokens.
   - Use the `mint` function (accessible to the owner) to mint additional tokens.
   - Transfer tokens between addresses using the `transfer` function.
   - Burn tokens using the `burn` function.
   - Use the `balanceOf` function to check the token balance of any address.
   - Use the `redeem` function to redeem tokens for in-game items.
   - The owner can use the `setItemCost` function to set the cost of items in tokens.

## Authors

- Metacrafter Chris
- [@metacraftersio](https://github.com/metacraftersio)

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

# CustomToken Contract

The CustomToken contract is an ERC20-compatible token implemented in Solidity. It provides functionalities for token minting, transferring, and burning.

## Explanation

- **Minting Tokens**: Only the contract owner can mint new tokens to a provided address.
- **Transferring Tokens**: Any user can transfer tokens to another address.
- **Burning Tokens**: Any user can burn their own tokens.

## Usage

1. **Deployment**:
   - Deploy the CustomToken contract on a supported Ethereum network (e.g., Remix, Ganache, Rinkeby, etc.).
   - Set the initial parameters such as token name and symbol during deployment.

2. **Minting Tokens**:
   - Call the `mint` function with the recipient's address and the amount of tokens to mint. This can only be done by the contract owner.

3. **Transferring Tokens**:
   - Users can transfer tokens by calling the `transferTokens` function with the recipient's address and the amount of tokens to transfer.

4. **Burning Tokens**:
   - Users can burn their tokens by calling the `burnTokens` function with the amount of tokens to burn.

## Deployment with Remix

1. Open Remix (https://remix.ethereum.org/) in your browser.
2. Create a new Solidity file and paste the CustomToken contract code.
3. Compile the contract using the Solidity compiler tab.
4. Go to the Deploy & Run Transactions tab.
5. Choose the desired environment (e.g., JavaScript VM, Injected Web3, etc.).
6. Set the parameters (name and symbol) and deploy the contract.

## Testing

1. After deployment, the owner can mint tokens using the `mint` function.
2. Users can transfer tokens using the `transferTokens` function.
3. Users can burn tokens using the `burnTokens` function.

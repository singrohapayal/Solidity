- **Purpose**: This is a basic Solidity contract for creating a custom ERC-20 token.
  
- **Variables**:
  - `tokenName`: Name of the token.
  - `tokenAbbrv`: Abbreviation of the token.
  - `totalSupply`: Total supply of the token.
  - `balances`: Mapping of Ethereum addresses to their token balances.

- **Functions**:
  - `mint`: Adds tokens to an address. Increases total supply and address balance.
  - `burn`: Removes tokens from an address. Decreases total supply and address balance.

- **Note**: This contract lacks some advanced features like access control and event logging, and it doesn't fully implement the ERC-20 standard.

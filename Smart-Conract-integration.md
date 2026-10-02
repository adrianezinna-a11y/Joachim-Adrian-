# Aura Protocol Smart Contract Integration

This guide provides the necessary data to interact with the Aura protocol Staking contract.

## Contract Details
*  **Network:** Sepolia testnet.
*  **Contract adress:**  `0x742d35Cc6634C0532925a3b844Bc454e4438f44e`

## Interacting With the Contract
Before making any function calls, *make sure you have imported the contract ABI into your work environment*.

To initiate a Staking transaction, you will call the main deposit function:
*  **Function:** `depositFunds`.
*  **Parameter:** `Amount` (must be formatted as a `Uint256` integar).
 >**Warning:** Transactions will revert if there isn't enough Sepolia ETH to cover the gas fees. *ensure your testnet is sufficiently funded before calling the contract*.

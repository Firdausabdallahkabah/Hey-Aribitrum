## Setting Up Arbitrum Environment
1. Configure MetaMask for Arbitrum Sepolia:
   -  I Connected to  MetaMask to the Arbitrum Sepolia Testnet following the setup in Module 3.1.
   -  I Confirmed the Arbitrum Sepolia network is active on MetaMask.

  ## Acquire Testnet ETH:
   -  I Used the Chainlink faucet to obtain Arbitrum Sepolia test ETH, or bridged Sepolia ETH via the Arbitrum Bridge.

 ## Writing the Smart Contract
## Created a New Smart Contract File:
   - Accessed [Remix IDE](https://remix.ethereum.org/), created a new workspace, and named the contract file HelloArbitrum.sol.

   ## Smart Contract Code:
   - Created a simple contract with:
     - A message state variable.
     - A constructor to set an initial message.
     - A public function updateMessage to update the message.

## Compiling and Deploying the Contract
Compiling the Contract:
   - Used the Solidity Compiler in Remix, ensuring compatibility with the specified Solidity version.
   - Resolved any errors encountered during compilation.

   ## Deploying to Arbitrum Sepolia:
   - I  Connected MetaMask to Remix and selected the Arbitrum Sepolia network.
   -  I Successfully deployed the contract and confirmed the transaction in MetaMask.

##  Interacting with the Contract
 Reading and Updating the Message:
   - I Verified the initial message using the message() function.
   - Used updateMessage to change the message and confirmed the update.

 Verifying on Arbiscan:
   -  I Copied the contract address from Remix, checked the contract on Arbiscan, and verified the deployment details.

###  Challenges and Solutions
- Challenge 1: Connecting MetaMask to the Arbitrum Sepolia network.
   - Solution:  I Followed detailed instructions from Module 3.1 to set up MetaMask.
- Challenge 2: Deploying the contract with test ETH.
   - Solution: Acquired test ETH using the Chainlink faucet and ensured sufficient balance for deployment.



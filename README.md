# zkSync Testnet Transactions: zkSync Sepolia 

This repo provides step-by-step instructions for executing transactions on the **zkSync testnet**, including adding zkSync Sepolia to MetaMask, bridging funds using the zkSync bridge, and verifying transactions.

---

## **Table of Contents**
1. [Introduction](#introduction)
2. [Adding zkSync Sepolia to MetaMask](#adding-zksync-sepolia-to-metamask)
3. [Getting Sepolia ETH](#getting-sepolia-eth)
4. [Bridging Funds](#bridging-funds)
5. [Verifying Transactions and Finality](#verifying-transactions-and-finality)
6. [Conclusion](#conclusion)

---

## **Introduction**
In this guide, we will:
1. Add **zkSync Sepolia Testnet** to **MetaMask**.
2. Get **Sepolia ETH** from the **Google Sepolia Faucet**.
3. Bridge funds to **zkSync Sepolia**.
4. Verify the transaction using the **zkSync Sepolia Block Explorer**.

---

## **Adding zkSync Sepolia to MetaMask**
1. **Add the Network:**
   - Visit [Chainlist](https://chainlist.org) and search for **zkSync Sepolia Testnet**.
   - Connect the network to your **MetaMask wallet** and follow the confirmation dialogs.
   - Ensure **testnets** are visible in your search settings.

   ![Chainlist Screenshot](https://github.com/jason-victor1/zkSync-first-transaction/blob/main/Chainlist%20screenshot.png?raw=true)

2. **Check Balance:**
   - View your Sepolia ETH balance in MetaMask or using the [zkSync Era Sepolia Block Explorer](https://sepolia.explorer.zksync.io/).
   - Make sure to switch the network to **zkSync Era Sepolia Testnet** in the zkSync Era Block Explorer.
   - Paste your MetaMask wallet address into the Block Explorer to see transaction history.

   ![zkSync Sepolia Added](https://github.com/jason-victor1/zkSync-first-transaction/blob/main/zkSync%20Sepolia%20testnet%20added%20.png?raw=true)

---

## **Getting Sepolia ETH**
- Use the **Google Sepolia Faucet** to obtain test ETH for Sepolia:
   - Visit [Google Sepolia Faucet](https://cloud.google.com/application/web3/faucet/ethereum/sepolia).
   - Submit your wallet address and confirm.  
     ![Ethereum Sepolia Faucet](https://github.com/jason-victor1/zkSync-first-transaction/blob/main/Ethereum%20Sepolia%20Faucet.png?raw=true)

   - Once received, the funds will appear in your MetaMask wallet:  
     ![Sepolia ETH Sent](https://github.com/jason-victor1/zkSync-first-transaction/blob/main/Ethereum%20Sepolia%20sent.png?raw=true)

   - Verify the transaction on Etherscan:  
     ![Etherscan Confirmation](https://github.com/jason-victor1/zkSync-first-transaction/blob/main/Etherscan%20confirmation.png?raw=true)

---

## **Bridging Funds**
You can transfer funds to **zkSync Sepolia** using the **zkSync bridge**.

1. **Using the zkSync Bridge**:
   - Visit the [zkSync bridge](https://bridge.zksync.io).
   - Ensure your wallet is connected to the **zkSync Sepolia Testnet**.
   - Go to the **menu options** in the **top-right corner** to switch the network to the **zkSync Sepolia Testnet**.

   ![zkSync Bridge Setup](https://github.com/jason-victor1/zkSync-first-transaction/blob/main/zkSync%20Bridge%20setup.png?raw=true)

   - Enter the amount to bridge (**0.025 ETH**) and confirm the transaction.

   ![Send ETH to Bridge](https://github.com/jason-victor1/zkSync-first-transaction/blob/main/Send%20over%20the%200.025%20.png?raw=true)

   - Confirm the bridge transaction:  
     ![Bridge Confirmation](https://github.com/jason-victor1/zkSync-first-transaction/blob/main/Bridge%20confirmation%20.png?raw=true)

2. **Types of Bridging Mechanisms**:
   - **Locking and Unlocking**: Tokens are locked on the **source chain** and unlocked on the **destination chain**.
   - **Minting and Burning**: Tokens are burned on the **source chain** and minted on the **destination chain**.
     - Example: USDC is burned and minted for seamless bridging

---

## **Verifying Transactions and Finality**

### **Transaction Status**
- Use the [zkSync Sepolia Block Explorer](https://sepolia.explorer.zksync.io/)) to check the status of your transaction:
   - On zkSync: The transaction status shows as **processed**.
   - On Ethereum: The status progresses through **sending, validating, and executing**.

   ![zkSync Status Processed](https://github.com/jason-victor1/zkSync-first-transaction/blob/main/zkSync%20Sepolia%20testnet%20confimation.png?raw=true)

### **Understanding Finality**
zkSync Era ties its **finality** and **security mechanisms** to the underlying **Ethereum Layer 1** blockchain. Finality involves the following steps:

1. **Batch Formation**: Transactions are grouped into a batch (generally takes a few minutes).
2. **Batch Commitment**: The batch is committed to the Ethereum blockchain.
3. **Proof Generation**: A cryptographic proof validating the batch is generated (takes ~1 hour).
4. **Proof Submission**: The proof is submitted to an Ethereum smart contract for verification.
5. **Batch Finalization**: The batch undergoes a final verification and settlement on Ethereum, with a delay of **~21 hours** as a security measure during zkSync's alpha phase.

> **Overall Finality Time:** ~24 hours (aligns with Ethereum block finality).

   ![zkSync Finality Process](https://github.com/jason-victor1/zkSync-first-transaction/blob/main/finality%20screenshot.png?raw=true)

---

### **Immediate Transaction Usability**
While full finality on zkSync Era can take up to **24 hours**, transactions are treated as **instantly confirmed** for a seamless user experience:
- **Immediate Transaction Display**: Transactions appear quickly in the UI and APIs as unconfirmed.
- **Immediate Asset Usability**: Transferred assets are immediately usable for further transactions, even within the same zkSync Era batch.

For cautious users, waiting for the full **finality process** ensures complete settlement and security.

---

## **Conclusion**
In this guide, we:
1. Added **zkSync Sepolia** to **MetaMask** using Chainlist.
2. Obtained Sepolia ETH using the **Google Sepolia Faucet**.
3. Bridged funds to zkSync Sepolia via the **zkSync bridge**.
4. Verified transaction details and learned about zkSync's **finality process**.
5. Discussed bridging mechanisms like **locking/unlocking** and **minting/burning**.

---

## **Resources**
- Chainlist: [chainlist.org](https://chainlist.org)
- zkSync Bridge: [zkSync Bridge](https://bridge.zksync.io)
- Google Sepolia Faucet: [Google Sepolia Faucet](https://cloud.google.com/application/web3/faucet/ethereum/sepolia)
- zkSync Block Explorer: [zkSync Explorer](https://sepolia.explorer.zksync.io/)




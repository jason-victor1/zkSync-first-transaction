# zkSync Testnet Transactions: zkSync Sepolia

This repository walks through executing transactions on the **zkSync testnet**, including bridging funds, verifying transactions, and understanding bridging mechanisms.

---

## **Table of Contents**
1. [Introduction](#introduction)
2. [Adding zkSync Sepolia to MetaMask](#adding-zksync-sepolia-to-metamask)
3. [Bridging Funds](#bridging-funds)
4. [Getting Sepolia ETH](#getting-sepolia-eth)
5. [Verifying Transactions](#verifying-transactions)
6. [Conclusion](#conclusion)

---

## **Introduction**
We will:
- Add **zkSync Sepolia** to MetaMask.
- Bridge funds from Sepolia to zkSync Sepolia.
- Verify transaction details using the **zkSync Sepolia Block Explorer**.

---

## **Adding zkSync Sepolia to MetaMask**
1. **Add the Network:**
   - Search for **zkSync Sepolia Testnet** on [Chainlist](https://chainlist.org).
   - Connect it to MetaMask and follow confirmation prompts.
   - Ensure testnets are visible in your search.

2. **Check Balance:**
   - View balances directly in MetaMask or on the [zkSync Era Sepolia Block Explorer](https://sepolia.zksync.io).
   - Paste your MetaMask wallet address to view account details.

---

## **Bridging Funds**
There are two methods to receive funds:
1. **Using a Faucet:**
   - Obtain test ETH via a faucet (requires APIs or GitHub login).

2. **Bridging:**
   - Transfer funds from the **Sepolia network** to **zkSync Sepolia**.
   - **Types of Bridging Mechanisms**:
     - **Locking and Unlocking:** Tokens are locked on the **source chain** and unlocked on the **destination chain**.
     - **Minting and Burning:** Tokens are burned on the **source chain** and minted on the **destination chain**.

---

## **Getting Sepolia ETH**
- Use a [recommended faucet](https://faucet.sepolia.io) to get test ETH.
- Suggested amount: **0.05 Sepolia ETH** for bridging.
- Retry after **10–20 minutes** if you encounter issues.

---

## **Verifying Transactions**
1. Use the [zkSync Bridge](https://bridge.zksync.io) to transfer funds.
2. Paste your wallet address into the **zkSync Sepolia Block Explorer** to view:
   - **Transaction Status:** Confirm the transaction is processed.
   - **Finality:**
     - Ethereum: ~13 minutes for settlement.
     - zkSync: ~24 hours with **ZK proofs** ensuring full validation.

---

## **Conclusion**
We covered:
- Adding **zkSync Sepolia** to MetaMask.
- Receiving funds via **faucet** or **bridging**.
- Using **zkSync Bridge** to transfer funds.
- Understanding **bridging mechanisms** like:
   - Locking/Unlocking
   - Minting/Burning
- Verifying transactions and understanding **finality** on zkSync Sepolia.

---

## **Resources**
- Chainlist: [chainlist.org](https://chainlist.org)
- zkSync Bridge: [zkSync Bridge](https://bridge.zksync.io)
- Sepolia Faucet: [Sepolia Faucet](https://faucet.sepolia.io)
- zkSync Block Explorer: [zkSync Explorer](https://sepolia.zksync.io)


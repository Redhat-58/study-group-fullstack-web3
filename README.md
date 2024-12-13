# grupo-de-estudos-fullstack-web3
# Web3 Communities

![Screenshot 2024-12-10 at 17 33 46](https://github.com/user-attachments/assets/442b12e4-3603-4283-a634-e0c8452e6f23)

Project developed in the fullstack web3 study group.

With the goal of showing how to develop a fullstack web3 application (frontend, backend, smart contracts), the Web3 Communities project was developed, a forum where only invited guests can access its exclusive posts.

**Features**

**Frontend**: 
- Wallet connection management (connect with your wallet)
- Authenticate by signing a message with the wallet
- Check the balance of our token
- If authenticated, see the exclusive posts
- Perform an invitation transaction to another wallet

**Backend**
- Auth: check if the signature sent is valid, if valid:
    - check the balance of the address in our token, if > 0: return a jwt
    - if less than 0: return 401
- Post: receives a call with the jwt, checks if the token is valid and returns the posts from that address


**Contracts**
- Standard erc20 token
- The contract deployment wallet would be the only one invited initially
- An address can only invite 3 other wallets
- Tools: Foundry & Hardhat




**Technologies used**

**Frontend/Backend**
- Next
- Wagmi
- Viem
- Rainbowkit
- JWT


**Contracts**
- Solidity
- Hardhat






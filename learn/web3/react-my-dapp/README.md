# Full Stack Ethereum Application 

App to deploy, and connect to a couple of basic smart contracts: 

1. A contract for creating and updating a message on the Ethereum blockchain
2. A contract for minting tokens, then allowing the owner of the contract to send tokens to others and to read the token balances, and for owners of the new tokens to also send them to others.

Tech used in the application:
1. Ethereum development environment (Solidity)
2. Ethereum Web Client Library (ethers.js)
3. Metamask
4. React

### Prerequisites
1. Node.js
2. MetaMask as browser extension

Try running some of the following tasks:

```shell
npm install ethers hardhat @nomiclabs/hardhat-waffle ethereum-waffle chai @nomiclabs/hardhat-ethers
npx hardhat
npx hardhat compile
npx hardhat node
npx hardhat run scripts/deploy.js --network localhost
npm install @openzeppelin/contracts

npm start
```
On React UI, some actions explored:

1. Read the greeting from the contract deployed to the blockchain
2. Update the greeting
3. Send the newly minted tokens from their address to another address
4. Once someone has received tokens, allow them to also send their tokens to someone else
5. Read the token balance from the contract deployed to the blockchain

![Hardhat node addresses](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/e176nc82ik77hei3a48s.jpg)
![MetaMask Localhost](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/qnbsbcm4y1md6cwjttpx.jpg)
![Import account](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/n7vbzlov869gwk9rtwl1.jpg)
![Imported account](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/x5lob4yug3jznhy9z0qt.jpg)
![Setting and getting the greeting value](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/9a57jbzrwylr2l0rujxm.png)
![Add token](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/0t2ip26i5d2ltjc9j2a6.jpg)
![NDT](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/5op32iqbeszizri72qc0.jpg)
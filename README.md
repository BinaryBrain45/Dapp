# Election - DApp

This project was part of the challenges assigned during the Global Hack Week by Major League Hacking. It's a decentralized application (DApp) for conducting secure, transparent elections on the Ethereum blockchain.

## Technologies Used
- Solidity
- JavaScript
- HTML/CSS
- Node.js
- Truffle
- Ganache
- Metamask

## Dependencies
Install these prerequisites:
- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/

## Installation Steps
1. **Clone the project:** `git clone https://github.com/BinaryBrain45/Dapp`
2. **Navigate to the project directory:** `cd election`
3. **Install dependencies:** `npm install`
4. **Start Ganache:** Open the Ganache GUI client. This will start your local blockchain instance.
5. **Compile & Deploy Election Smart Contract:** Run `truffle migrate --reset`. You must migrate the election smart contract each time you restart Ganache.
6. **Configure Metamask:** Unlock Metamask, connect it to your local Ethereum blockchain provided by Ganache, and import an account provided by Ganache.
7. **Run the Front End Application:** Run `npm run dev` and visit http://localhost:3000 in your browser.

## Contribution Guidelines
We welcome contributions from the community! To contribute:
1. Fork this repository.
2. Create a new branch for your changes.
3. Submit a pull request with your proposed changes.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

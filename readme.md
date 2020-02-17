<u>***Notes from JavaScript Meetup @ Headout, Bangalore***</u>

<h1>Tools required:</h1>

<div>

1. **Ganache** <a href="https://www.trufflesuite.com/ganache">(Download)</a>: Tool to help you host your local blockchains. Think of it as IIS or XAMP/LAMP.
2. **Truffle**:  ```npm install truffle -g``` to install Truffle. It is used to automate development tasks like adding a block to your blockchain, migrating all changes, testing etc. Think of it as manage.py from Django.
3. **Web3** ( ```npm install web3``` ): Used to talk to your Blockchain </div>

<div><h1>How to</h1>

1. ```git clone https://github.com/dappuniversity/social-network main```
2. ```cd main```
3. ```npm install```
4. Open up Ganache and start a Blockchain at the server mentioned in truffle-config.js
5. ```npm start```
6. Install Metamask, a Crypto Wallet
7. Go to Ganache, next to account there will be a key icon, click on it, copy the longer string
8. Import account into Metamask
9. Make a post
10. Confirm Transaction.
11. There you go.
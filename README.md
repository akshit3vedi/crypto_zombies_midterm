Team Members -

Akshit Trivedi (885152926)
Meet Zaveri (884477886)
Dharmil Dhameliya
Vrund Thakkar (829589241)

Improvements -

1. Built a better UI
2. Change the starter-code to not hard coded
3. Creation of multiple zombie using same account
4. You can select which zoombies needed to be level up
5. Added Delete Zombie functionality
6. Shown unique image for every zombie using their DNA


Used the provided starter code

Video Link - https://www.youtube.com/watch?v=H1rX7Xio1Mo

You should have node js , ganache, truffle, solidity installed on your local machine.
Truffle v5.4.25
Ganache v2.5.4
Solidity - 0.8.11 (solc-js) 
Node v14.16.0
Web3.js v1.2.7
Metamask

Steps -

1. run npm i
2. Connect ganache by linking truffle-config.js file
3. run truffle compile
4. run truffle migrate
5. Open Metamask
6. Connect Ganache network to Metamask :
   Network Name: Ganache
   New RPC URL: http://localhost:7545
   Chain ID: 1337 (according to your network id)
   Symbol: ETH
7. From accounts section copy any private key and create new account on metamask
8. In index.html change the cryptoZombiesAddress from your ganache key
9. run http-start

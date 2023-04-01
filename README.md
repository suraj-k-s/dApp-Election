
# Election - DAPP Tutorial
Build your first decentralized application, or Dapp, on the Ethereum Network with this tutorial!




Follow the steps below to download, install, and run this project.

## Dependencies
Install these prerequisites to follow along with the tutorial. See free video tutorial or a full explanation of each prerequisite.
- Visual Studio Code : https://code.visualstudio.com/docs/?dv=win
- NPM: https://nodejs.org/dist/v18.15.0/node-v18.15.0-x64.msi
- Truffle: install on visual studio code in extention section
- Ganache: https://github.com/trufflesuite/ganache-ui/releases/download/v2.7.0/Ganache-2.7.0-win-x64.appx
- Metamask: https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn


## Step 1. Clone the project
`git clone https://github.com/suraj-k-s/dApp-Election.git`

## Step 2. Install dependencies
```
$ cd dApp-Election
$ npm install
```
## Step 3. Start Ganache
Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance. See free video tutorial for full explanation.


## Step 4. Compile & Deploy Election Smart Contract
`$ truffle migrate --reset`
You must migrate the election smart contract each time your restart ganache.

## Step 5. Configure Metamask
See free video tutorial for full explanation of these steps:
- Unlock Metamask
- Connect metamask to your local Etherum blockchain provided by Ganache.
- Import an account provided by ganache.

## Step 6. Run the Front End Application
`$ npm run dev`
Visit this URL in your browser: http://localhost:3000



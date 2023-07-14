# Basic NFT Marketplace end to end

* This code is for the Tutorial [Build your own NFT Marketplace from Scratch](https://docs.alchemy.com/alchemy/) built by [alchemy.com](https://alchemy.com)

<b>Step 0: Sign up for an Alchemy account and create a new app</b>

<img width="1792" alt="1" src="https://github.com/Zanyi09/NFT-Project/assets/137127068/b45117dc-c091-4690-b14c-8e43a5630bc2"><br>
* Fill in the details on the popup to get your new key. For this tutorial, you should choose "Ethereum" as the chain and "Goerli" as the test network.<br>

![2](https://github.com/Zanyi09/NFT-Project/assets/137127068/16a08b25-7cad-4733-bfb5-1ab95f8c80c5)<br>
<b>Step 1: Set up your MetaMask wallet for development</b> <br>
* If you already have MetaMask with a Goerli address and at least 0.1 Goerli ETH on it, skip toStep 2.

If you do not have a Goerli address, connect MetaMask to the Goerli network, and then use a Goerli faucet to request Goerli ETH. You will need Goerli ETH to deploy smart contracts and upload NFTs to your NFT marketplace.

Make sure you add the below details when adding a new network:

* Network Name: Goerli Test Network

* RPC base URL: https://eth-goerli.g.alchemy.com/v2/{INSERT YOUR API KEY}

* Chain ID: 5

* Block Explorer URL: https://goerli.etherscan.io/

* Symbol (Optional): ETH<br>
<b>Step 2: Set up the repository</b><br>
* git clone https://github.com/Zanyi09/NFT-Project.git<br>
* cd NFT-Project<br>
* npm install<br>
* npm start
<br>
<b>Step 3: Set up your environment variables and Hardhat config</b><br>
Create a new .env file in the root of your project, which is right inside the RTW3-Week7-NFT-Marketplace folder, and add:<br>
* The Alchemy API URL that you created in Step 1<br>
* The private key of the MetaMask wallet that you will use for development<br>
* When you're done, your .env file should look like this:<br>

<b>JSON<br>
REACT_APP_ALCHEMY_API_URL="<YOUR_API_URL>"<br>
REACT_APP_PRIVATE_KEY="<YOUR_PRIVATE_KEY>"</b>
<br>
<b>Step 4: Use Piñata to upload your data to IPFS</b><br>
If you don't have a Piñata account, sign up for a free Piñata account and verify your email.<br>

Create your Piñata API key
To create your Piñata key:<br>

* Navigate to https://pinata.cloud/keys<br>
* Select the "New Key" button at the top<br>
* Set the Admin widget as enabled<br>
* Name your key<br>

<b>Step 5: Understand the requirements</b><br>
<img width="1496" alt="e4520c5-dog" src="https://github.com/Zanyi09/NFT-Project/assets/137127068/c1f2ceed-4fef-4b03-a5e8-17884c820020">
<br>
<b>List NFT page</b><br>
<img width="1512" alt="23374cc-mar" src="https://github.com/Zanyi09/NFT-Project/assets/137127068/c93f6104-e904-4b72-baf1-0e99920da57f">
<br>
<b>Marketplace home page</b><br>
<img width="1496" alt="b0e0f55-user_prof" src="https://github.com/Zanyi09/NFT-Project/assets/137127068/64b67d18-84c6-4ec8-8fb9-c10540a3f25b">




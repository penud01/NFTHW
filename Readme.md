# Create your own NFT using moralis

DEEPIKA RAJASHREE PENUBALLI

First, we need to sign up to the tab, to integrate with metamask.
We can interact with the services after signing up - choose a file - we want to mint and name the NFT
Give a description to the NFT.
We send the transaction to the contract, for us to access it - in collections we can see it. 
Details - what kind of nlockchain/NFT etc.
Initially run run.py - which initializes all other files required.
index - has all elements of DAPP to interact with metamask.
Analyzing the logic - 
Electronic records contains metadata. When you mint NFT - Linking token with metadata is the main task.
we can use Moralis to capture and handle the file objects - it supports multiple methods - centralized or decentralized.
When We save image to IPFS, we get two values - Hash & a URL (IPFS gateway) - this is done by Moralis
After the metadata is available - with the javascript object created and saved to IPFS - we can call the mint token function.
Minting is done by interacting with smart contract.
ERC721 contract is used for this project.
After we get the transaction hash, we understand that the transaction is in progress - we can now print output to the user that NFT is being minted.


Below are the requirements:
1. Requires python3, if you don't have it there are multiple resources online on how to install it according to your platform.
2. Set a virtual environment with `Python3 -m venv venv`
3. Initialize your virtual environment with `source venv/bin/activate` (For Mac and Linux).
4. Intall the dependencies with `pip install -r requirements.txt`


---
title: "NFT Marketplace for Ethereum Blockchain"
excerpt: "
<p align='left'>
    <img src='https://raw.githubusercontent.com/NFTSuits/NFT-Marketplace-DApp/main/NFTSuits%20icons/nftSuits_logo.png' width='300' height='360'/>
</p>
<h2>Tech Stack</h2>
<ul>
    <li><b>Client: </b>React, Recoil, Material UI </li>
    <li><b>Contract: </b>Solidity </li>
    <li><b>Dev Tools: </b>Ganache, Truffle, Remix, Docker </li>
    <li><b>Static Smart Contract Analysis: </b>Securify 2.0, Slither </li>
    <li><b>Testing: </b>Mocha </li>
</ul>
"
collection: portfolio
---
<p align="center">
    <img src="https://raw.githubusercontent.com/NFTSuits/NFT-Marketplace-DApp/main/NFTSuits%20icons/nftSuits_logo.png"/>
</p>

# NFT Marketplace for Ethereum Blockchain

NFT Suits is a game that centered around collectible unique items that are used to create one-of-a-kind avatars where the uniqueness is guaranteed by ERC721 protocol.  No items can be replicated, taken away, or destroyed, since the proof of ownerships are stored on Ethereum blockchain. In order to see the items and interact with the marketplace, user has to installMetaMask extension to her/his browser. Then, by connecting his/her wallet; the user can buy, bid on, offer items for auction and sell the items via the marketplace. As tree requiredand complementary pieces are purchased and worn, an avatar is created and displayed to the community.

# README Contents
1. [Authors](#authors)
2. [Tech Stack](#tech-stack)
3. [Deliverables](#deliverables)
4. [Features](#features)
    - [Within her/his profile, a user can](#within-profile-page-a-user-can)
    - [Within the item page, a user can](#within-the-item-page-a-user-can)
5. [How to Run Docker](#how-to-run-docker)
6. [Screenshots](#screenshots)
7. [Support and Feedback](#support-and-feedback)

## Authors
<!-- <p align="center">
    <img src="website/src/containers/index/team_bidis.png"/>
</p> -->

- [@cavitcakir](https://www.github.com/cavitcakir)
- [@kayakapagan](https://www.github.com/kayakapagan)
- [@gorkemkose](https://www.github.com/gorkemkose)
- [@gokberkyar](https://www.github.com/gokberkyar)

## Tech Stack

**Client:** React, Recoil, Material UI

**Contract:** Solidity

**Dev Tools:** Ganache, Truffle, Remix, Docker

**Static Smart Contract Analysis:** Securify 2.0, Slither

**Testing:** Mocha

<p align="center">
    <img  src="https://raw.githubusercontent.com/NFTSuits/NFT-Marketplace-DApp/main/NFTSuits%20icons/react-logo.png"      style="width:50px;"/>
    <img  src="https://raw.githubusercontent.com/NFTSuits/NFT-Marketplace-DApp/main/NFTSuits%20icons/recoil-logo.svg"     style="width:50px;"/>
    <img  src="https://raw.githubusercontent.com/NFTSuits/NFT-Marketplace-DApp/main/NFTSuits%20icons/materialUI-logo.png" style="width:50px;"/>
    <img  src="https://raw.githubusercontent.com/NFTSuits/NFT-Marketplace-DApp/main/NFTSuits%20icons/solidity-logo.jpeg"  style="width:50px;"/>
    <img  src="https://raw.githubusercontent.com/NFTSuits/NFT-Marketplace-DApp/main/NFTSuits%20icons/ganache-logo.png"    style="width:50px;"/>
    <img  src="https://raw.githubusercontent.com/NFTSuits/NFT-Marketplace-DApp/main/NFTSuits%20icons/truffle-logo.png"    style="width:50px;"/>
    <img  src="https://raw.githubusercontent.com/NFTSuits/NFT-Marketplace-DApp/main/NFTSuits%20icons/remix-logo.png"      style="width:50px;"/>
    <img  src="https://raw.githubusercontent.com/NFTSuits/NFT-Marketplace-DApp/main/NFTSuits%20icons/docker-logo.png"     style="width:50px;"/>
    <img  src="https://raw.githubusercontent.com/NFTSuits/NFT-Marketplace-DApp/main/NFTSuits%20icons/securify-logo.png"   style="width:50px;"/>
    <img  src="https://raw.githubusercontent.com/NFTSuits/NFT-Marketplace-DApp/main/NFTSuits%20icons/slither-logo.png"    style="width:50px;"/>
    <img  src="https://raw.githubusercontent.com/NFTSuits/NFT-Marketplace-DApp/main/NFTSuits%20icons/mocha-logo.svg"      style="width:50px;"/>
</p>

## Deliverables
   - [website (make sure you are in Ropsten Test Network)](https://nftsuits.com/)
   - [report](https://github.com/cs48kblockchain/NFTSuits-DApp/blob/main/NFTSuitsExplained.pdf)
   - [presentation](https://github.com/cs48kblockchain/NFTSuits-DApp/blob/main/Presentation.pdf)

## Features

### Within profile page, a user can

- Set a username
- Withdraw her/his balance
- Create an avatar with the items that (s)he owns by wearing
- Save the item and display it in the avatars page
- List his/her items with certain filtering options
- See his/her statistics

### Within the item page, a user can

- Sell her/his item for a fixed price
- Cancel sale for his/her item
- Buy an item
- Create an auction for his/her item
- Cancel an auction for his/her item
- Accept the highest bid
- Bid on an item
- Withdraw his/her bid
- Wear his/her item under some condition
- Unwear his/her item under some condition
- List all of the items with certain filtering options
 
## How to Run Docker

```bash
    ## in project directory, i.e. cd project
    docker-compose -f docker-compose.dev.yml up
```

## Running Tests
To run tests, run the following command

```bash
  ## make sure ganache is running
  cd truffle
  truffle test
```

## Screenshots
<p align="center">
    <h3>Landing Page</h3>
    <img src="https://raw.githubusercontent.com/NFTSuits/NFT-Marketplace-DApp/main/NFTSuits%20images/landing-page.png"/>
</p>
<p align="center">
    <h3>Market Place</h3>
    <img src="https://raw.githubusercontent.com/NFTSuits/NFT-Marketplace-DApp/main/NFTSuits%20images/marketplace-page.png"/>
</p>
<p align="center">
    <h3>Item Page Example 1</h3>
    <img src="https://raw.githubusercontent.com/NFTSuits/NFT-Marketplace-DApp/main/NFTSuits%20images/item-example-1.png"/>
</p>
<p align="center">
    <h3>Item Page Example 2</h3>
    <img src="https://raw.githubusercontent.com/NFTSuits/NFT-Marketplace-DApp/main/NFTSuits%20images/item-example-2.png"/>
</p>
<p align="center">
    <h3>Profile Page</h3>
    <img src="https://raw.githubusercontent.com/NFTSuits/NFT-Marketplace-DApp/main/NFTSuits%20images/profile-page.png"/>
</p>
<p align="center">
    <h3>Avatars Page</h3>
    <img src="https://raw.githubusercontent.com/NFTSuits/NFT-Marketplace-DApp/main/NFTSuits%20images/avatar-page.png"/>
</p>

## Support and Feedback

Feel free to create an issue to discuss more.

  










 Hardhat NextJS Marketplace

This is a repo showing how to make an NFT Marketplace from scratch!


Full Repo

    Hardhat NFT Marketplace
    Getting Started
        Requirements
        Quickstart
        Typescript
            Optional Gitpod
    Usage
        Testing
    Deployment to a testnet or mainnet
    Thank you!

Getting Started
Requirements

    git
        You'll know you did it right if you can run git --version and you see a response like git version x.x.x
    Nodejs
        You'll know you've installed nodejs right if you can run:
            node --version and get an ouput like: vx.x.x
    Yarn instead of npm
        You'll know you've installed yarn right if you can run:
            yarn --version and get an output like: x.x.x
            You might need to install it with npm

Quickstart

git clone https://github.com/PatrickAlphaC/hardhat-nextjs-nft-marketplace-fcc
cd hardhat-nextjs-nft-marketplace-fcc
yarn

Typescript

TODO!!

For the typescript edition, run:

git checkout typescript

Optional Gitpod

If you can't or don't want to run and install locally, you can work with this repo in Gitpod. If you do this, you can skip the clone this repo part.

Open in Gitpod

    Remember if you are using gitpod then you cannot connect your local hardhat node with metamask. To resolve this you can use vs code or testnets instead of local node.

Usage

Deploy:

yarn hardhat deploy

Testing

yarn hardhat test

Deployment to a testnet or mainnet

    Setup environment variabltes

You'll want to set your KOVAN_RPC_URL and PRIVATE_KEY as environment variables. You can add them to a .env file, similar to what you see in .env.example.

    PRIVATE_KEY: The private key of your account (like from metamask). NOTE: FOR DEVELOPMENT, PLEASE USE A KEY THAT DOESN'T HAVE ANY REAL FUNDS ASSOCIATED WITH IT.
        You can learn how to export it here.
    KOVAN_RPC_URL: This is url of the kovan testnet node you're working with. You can get setup with one for free from Alchemy

    Get testnet ETH

Head over to faucets.chain.link and get some tesnet ETH. You should see the ETH show up in your metamask.

    Deploy

yarn hardhat deploy --network kovan

Thank you!

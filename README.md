## IOTA EVM NFT Marketplace

### Running this project

#### Local setup

To run this project locally, follow these steps.

1. Clone the project locally, change into the directory, and install the dependencies:

```sh
git clone https://github.com/ledgerluminary55/spaceseven

cd iota-evm-nft-marketplace

# install using NPM
npm install
```

2. Deploy

Create copy `.env.example`, rename it to `.env` and add a private key.

```sh
npx hardhat run scripts/deploy.js --network iscp
```

4. Start the app

```
npm run dev
```

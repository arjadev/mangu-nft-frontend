# Mangu NFT Frontend

A React-based frontend application for minting and managing NFTs, built on top of the HashLips NFT minting dapp template.

## Features

- Connect to Ethereum wallet (MetaMask)
- Mint NFTs from your smart contract
- View your minted NFTs
- Responsive design
- Redux state management

## Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- MetaMask wallet browser extension
- Ethereum network access

## Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/mangu-nft-frontend.git
cd mangu-nft-frontend
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

## Configuration

1. Update the smart contract address in `src/config.js`
2. Configure your network settings in `src/config.js`
3. Update any other configuration parameters as needed

## Development

To start the development server:

```bash
npm start
# or
yarn start
```

The application will be available at `http://localhost:3000`

## Building for Production

To create a production build:

```bash
npm run build
# or
yarn build
```

The build files will be created in the `build` directory.

## Project Structure

```
src/
├── components/     # React components
├── config/        # Configuration files
├── redux/         # Redux store and actions
├── styles/        # Styled components
└── utils/         # Utility functions
```

## Dependencies

- React 17.0.2
- Redux 4.1.1
- Web3.js 1.5.1
- Styled Components 5.3.0

## License

MIT License - See LICENSE file for details

## Acknowledgments

- Based on HashLips NFT minting dapp template
- Created by Daniel Eugene Botha (HashLips)

# Awesome list of EVM indexing tools and libraries

### The Graph: an indexing protocol for querying networks like Ethereum and IPFS.
- https://thegraph.com
- Anyone can build and publish open APIs, called subgraphs, making data easily accessible.

### indexer.xyz: Crypto datasets. Open, real-time, decoded. Powered by Goldsky
- https://github.com/indexed-xyz/docs
- The Indexed Dataset is a permanently free, public domain, CC0 licensed dataset for doing analysis on near real-time data on blockchains. The dataset is backed by an alliance of web3 and cloud organizations with the goal of providing a way to easily analyze data from your laptop or servers without being locked into any specific cloud.

### Subsquid: Where Web3 devs go to get blockchain data.
- https://subsquid.io
- A peer-to-peer network to batch query and aggregate terabytes of on-chain and off-chain data in a ridiculously efficient way.

### reth-indexer
- https://github.com/joshstevens19/reth-indexer
- reth-indexer reads directly from the reth db and indexes the data into a postgres database all decoded with a simple config file and no extra setup alongside exposing a API ready to query the data.

### Reservoir Protocol Indexer: Reservoir's open-source indexer constructs the global NFT orderbook
- https://github.com/reservoirprotocol/indexer
- The Reservoir Indexer is an open-source node responsible for reading from and writing to the Data Lake and reconstructing the Global NFT Orderbook. The Indexer combines raw order data from Arweave, with ownership data from Ethereum, to trustlessly reconstruct the state of the orderbook and provides open APIs for interacting with the data.

### evm-indexer: A scalable SQL indexer for EVM compatible blockchains
- https://github.com/eabz/evm-indexer
- This indexer is specifically created to parse known data for EVM compatible chains. It stores all the blockchain primitives (blocks, transactions, receipts, logs, traces, withdrawals) and some other useful information (contracts created, dex trades, erc20 transfers, erc721 transfers, erc1155 transfers)

### dna: Apibara Direct Node Access and SDK
- https://github.com/apibara/dna
- Apibara is the fastest platform to build production-grade indexers that connect onchain data to web2 services.

### ethereum-indexer-public: Ethereum indexer and APIs
- https://github.com/rarible/ethereum-indexer-public
- NFT indexer — is used to index all history of NFTs related actions, i.e., mint, transfer, and burn. Indexer gets logs from an Ethereum network, and accordingly creates NFT items in a NoSQL database. Especially, it listens to a change of a state of an NFT item ownership. ERC-20 indexer — is responsible for tracking user balances. If we mapped it to the Rarible usage, it checks if a user has enough of a given currency to make a bid. It handles all the information about a user's wallet status. Order indexer — aggregates data about Orders from different platforms. In order to properly display order information (order means intent, e.g., intent to sell, or in simpler words, intent to sell an NFT for a given price), we need an order price in addition to other properties.

### Ponder: A backend framework for crypto apps
- https://ponder.sh
- Ponder is an open-source framework for blockchain application backends. With Ponder, you can build a GraphQL API for any set of smart contracts on Ethereum-based blockchains with hot reloading, type safety, and easy deployment to production.

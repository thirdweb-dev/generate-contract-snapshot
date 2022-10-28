# Generate contract snapshot

Get a JSON with the owners and the quantity of each owned item for any ERC721 or ERC1155 contract, on any chain.

## Usage

- Install dependencies
  
  ```bash
  npm install
  # or
  yarn
  ```

- Replace `NETWORK.ETH_MAINNET` on `alchemySettings` with the Chain you're using.
- Replace `ethereum` on thirdweb SDK initialization with the Chain you're using. (Example: `"polygon"`, `"avalanche"`, `"fantom"` )
- Replace the `erc` const with either `erc1155` or `erc721`, depending on your needs.
- Replace contractAddress, network and tokenId (in case of erc1155) with the contract address to take a snapshot of.
- Run with `npx ts-node index.ts`


## Convert to CSV

Convert for Snapshot/Airdrop compatible with thirdweb by uploading `output.json` to [convertcsv.com](https://www.convertcsv.com/json-to-csv.htm)
# NFT Management Script

## Overview

This JavaScript script is designed to manage NFTs (Non-Fungible Tokens) by allowing you to mint new NFTs, list all minted NFTs, and get the total number of NFTs created. It uses a simple array to store NFT data and provides functions to interact with this data.

## Features

- **Minting**: Create and add new NFTs with metadata.
- **Listing**: Display the metadata of all NFTs in the system.
- **Counting**: Get the total number of NFTs that have been minted.

## Code Overview

### Variables

- **`arr`**: An array that stores all NFT objects.

### Functions

#### `mintNFT(name, religion, gender, age, height)`

- **Description**: Creates a new NFT with the provided metadata and adds it to the `arr` array.
- **Parameters**:
  - `name`: The name associated with the NFT.
  - `religion`: The religion associated with the NFT.
  - `gender`: The gender associated with the NFT.
  - `age`: The age associated with the NFT.
  - `height`: The height associated with the NFT.
- **Usage Example**:
  ```javascript
  mintNFT("John Doe", "Christianity", "Male", "30", "5.9");

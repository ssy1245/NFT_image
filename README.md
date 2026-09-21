# Campus Memo NFT Collection

A limited-edition commemorative NFT collection created for the **HKU Drone Club**, as part of the COMP7610 Smart Contract Lab.

The collection consists of 10 unique NFTs featuring a cute yellow mascot in a pixel-art, Perler bead-inspired style. Each NFT represents a different moment from the club's drone adventures.

## Collection Overview

![Campus Memo NFT Collection](NFT_List/NFT.png)

The image above displays the complete Campus Memo NFT collection.

## NFT Collection

| Token ID | NFT Image                 | Metadata                    |
| -------- | ------------------------- | --------------------------- |
| #1       | [1.png](NFT_List/1.png)   | [1.json](metadata/1.json)   |
| #2       | [2.png](NFT_List/2.png)   | [2.json](metadata/2.json)   |
| #3       | [3.png](NFT_List/3.png)   | [3.json](metadata/3.json)   |
| #4       | [4.png](NFT_List/4.png)   | [4.json](metadata/4.json)   |
| #5       | [5.png](NFT_List/5.png)   | [5.json](metadata/5.json)   |
| #6       | [6.png](NFT_List/6.png)   | [6.json](metadata/6.json)   |
| #7       | [7.png](NFT_List/7.png)   | [7.json](metadata/7.json)   |
| #8       | [8.png](NFT_List/8.png)   | [8.json](metadata/8.json)   |
| #9       | [9.png](NFT_List/9.png)   | [9.json](metadata/9.json)   |
| #10      | [10.png](NFT_List/10.png) | [10.json](metadata/10.json) |

## Token Information

* **NFT Name:** Campus Memo
* **Maximum Supply:** 10 NFTs
* **Minting Cost:** 100 CPT per NFT
* **NFT Standard:** ERC-721
* **Payment Token:** Club Token (CPT)

Each NFT has a unique token ID and its own metadata file.

## Repository Structure

```text
NFT_image/
├── README.md
│
├── NFT_List/
│   ├── NFT.png
│   ├── 1.png
│   ├── 2.png
│   ├── ...
│   └── 10.png
│
└── metadata/
    ├── 1.json
    ├── 2.json
    ├── ...
    └── 10.json
```

`NFT.png` is the complete collection overview, while `1.png` through `10.png` are the individual NFT images.

## NFT Metadata

Each NFT has a corresponding JSON file containing its name, description, and image URL.

Example: `metadata/1.json`

```json
{
  "name": "Campus Memo #1",
  "description": "Limited-edition commemorative NFT for the HKU Drone Club.",
  "image": "https://raw.githubusercontent.com/ssy1245/NFT_image/main/NFT_List/1.png"
}
```

The CampusMemo smart contract will use these metadata files to provide the URI for each NFT.

## Project Purpose

This collection was created for educational purposes to demonstrate ERC-721 NFT minting and interaction with an ERC-20 token through Solidity smart contracts.


# NFT Minting

This code serves as an illustrative example demonstrating the process of minting non-fungible tokens (NFTs) in Cadence on the Flow blockchain. It provides a foundational template that can serve as a starting point for the development of customized NFTs on the Flow network. Developers can leverage this code as a basis for creating their own unique non-fungible tokens with specific properties and behaviors on the Flow blockchain.

## Description

This program, written in Cadence, serves as a straightforward contract that enables users to mint Non-Fungible Tokens (NFTs). Initially, it establishes a collection within the account address specified by the owner. Subsequently, the program prompts the user for input, including details such as address, username, lucky number, favorite food, and more. Using this input, the contract proceeds to mint a unique NFT, allowing for the creation of personalized and distinct tokens on the Flow blockchain.

## Requirements

To run this code, you will need the following:

1)A Flow account with sufficient FLOW tokens to pay for the transaction fees

2)The Flow CLI tool installed on your machine

3)A code editor or IDE for modifying the code
## Usage

To use this code to mint your own NFTs on the Flow blockchain, follow these steps:

1)Clone this repository to your local machine.

2)Open the nft-mint.cdc file in your code editor or IDE.

3)Modify the metadata dictionary to include the metadata for your NFTs, such as the name, description, and image URL.

4)Modify the mintNFT function to specify the total number of NFTs you want to mint and the price of each NFT.

5)Save the nft-mint.cdc file.

6)Open a terminal window and navigate to the directory where you cloned this repository.

7)Run the following command to deploy the contract to the Flow blockchain:
flow project deploy

8)Once the contract is deployed, run the following command to mint your NFTs:
flow transactions send ./transactions/mintNFT.cdc

9)Enter your Flow account credentials when prompted.

10)Wait for the transaction to be confirmed on the Flow blockchain.
## License

This code is licensed under the [MIT](https://choosealicense.com/licenses/mit/) license.See the LICENSE file for more information.


## Acknowledgements

This code was inspired by the Flow NFT Tutorial on the Flow documentation website. Special thanks to the Flow team for creating such a powerful and developer-friendly blockchain platform!

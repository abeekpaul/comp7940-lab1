# Blockchain Simulation in Python

This Python script simulates a simple blockchain and transaction system using ECC (Elliptic Curve Cryptography) for key generation and ECDSA (Elliptic Curve Digital Signature Algorithm) for transaction signing and verification.

## Requirements

- Python 3.x
- pycryptodome
- cryptography

## Installation

To install the required packages, run the following command:
!pip install pycryptodome !pip install cryptography

## Usage

The script defines several functions and classes to simulate the creation and verification of transactions, building of a Merkle tree, and the addition and validation of blocks in a blockchain.

### Key Features

- **ECC Key Generation**: Generate a private-public key pair using ECC.
- **Transaction Creation**: Create a signed transaction with a unique ID.
- **Merkle Tree**: Build and verify a Merkle tree for transaction hashes.
- **Blockchain**: Add blocks to the chain and verify the integrity of the entire blockchain.

### How to Run

Simply execute the script in a Python environment. The script will automatically generate transactions, build a Merkle tree, and add blocks to the blockchain.

## Example Output

The script will output the details of the generated transactions, the verification of the Merkle tree, and the status of the blockchain's integrity.

## Note

This script is for educational purposes and simulates a blockchain in a simplified manner. It does not interact with any real-world cryptocurrency networks.

## License

This script is released under the MIT License.

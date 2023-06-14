# blockchain3

# Simple Blockchain

This is a simple implementation of a blockchain using Python. It consists of two classes: `Block` and `Blockchain`.

## Block

The `Block` class represents an individual block in the blockchain. Each block has the following attributes:

- `index`: The index or position of the block within the blockchain.
- `timestamp`: The timestamp indicating when the block was created.
- `data`: The data associated with the block.
- `previous_hash`: The hash of the previous block in the chain.
- `hash`: The hash of the current block calculated using the SHA256 algorithm.

### Methods

- `calculate_hash()`: Calculates the hash of the block using the block's attributes.
- `__init__(self, index, timestamp, data, previous_hash)`: Initializes a new instance of the `Block` class.

## Blockchain

The `Blockchain` class represents the blockchain itself. It has the following attributes:

- `chain`: A list that holds all the blocks in the blockchain.

### Methods

- `create_genesis_block()`: Creates the genesis block (the first block in the blockchain).
- `add_block(data)`: Adds a new block to the blockchain.
- `__init__(self)`: Initializes a new instance of the `Blockchain` class.

## Usage

To use the blockchain implementation, follow these steps:

1. Import the required modules:

   ```python
   import hashlib
   import json
   import time
   
Define an instance of the Blockchain class:

    ```python
      blockchain = Blockchain()
      
Add blocks to the blockchain using the add_block(data) method:

    ```python
      blockchain.add_block("Block 1")
      blockchain.add_block("Block 2")
    
To print the contents of the blockchain, iterate over the blocks in the chain attribute:

    ```python
      for block in blockchain.chain:
          print(block.__dict__)
The output will display the attributes of each block in the blockchain.

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute this code for educational and personal projects.

If you have any questions or feedback, please feel free to contact me.

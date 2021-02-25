# Very Simple Blockchain Implementation in Go.
1. main.go includes command-line interface
2. block.go includes block structure , CreateBlock method and few others related to creating and serializing the block for database.
3. blockchain.go responsable for creating main chain, adding blocks to the chain and validating blocks.

# User Manual
1. Install golang compiler
2. For inspaction of the created chain : ```go run main.go print```
3. For adding nwe block to the chain:  ```go run main.go add --block [BLOCK_DATA]```

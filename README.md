# Blockchain
A repository of private blockchains with different consensus algorithms and developed on the Ethereum Blockchain.

## Index

- [Features](https://github.com/Santiago-Pedemonte/Private-Blockchains#features)
- [How to use](https://github.com/Santiago-Pedemonte/Private-Blockchains#how-to-use)
- [Resources](https://github.com/Santiago-Pedemonte/Private-Blockchains#resources)

## Features

### Network

Each network has had a genesis block generated and is fully functioning (transactions have been made successfully during testing). The relevant network Id, network name, and other specifications can be found in the appropriate 'Keys, etc....txt' file or on the networkname.json file (substituting networkname for the actual name of the network.

So far, two different networks have been added with different consensus protocols (for more information on consensus protocols please refer to the [notes](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Notes%20on%20Different%20Consensus%20Algorithms.md) on the different consensus algorithms.

### Nodes

Each Blockchain contains two node files. These are full nodes that have already been initialized on the network- for more information on node creation and initialization, please refer to the [node guide](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Node%20Creation%20and%20Initialization.md).

The first and second nodes have been conveniently-named 'firstNode' and 'secondNode', respectively. Each of these nodes had a personal account created at the moment they were generated. The key pair for accessing the nodes' wallets (in the appropriate network) can be found in the relevant 'Keys, etc....txt' file. Likewise, when using [MyCrypto](https://mycrypto.com/), one can also use the keystore file located in each of the nodes' folders.
For more information on the MyCrypto app, please refer to the [installation guide](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Installation%20Guides.md#installing-mycrypto-desktop-app)

The commands for starting each of the nodes are also included in the 'Keys, etc....txt' file.

## How to use
**Note: Geth should already be installed prior to booting up and using the network. Please refer to the [install guide](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Installation%20Guides.md#installing-go-ethereum-tools)**



## Resources

-[Useful links](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Useful%20Links.md)
-[Blockchain FAQs](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Blockchain%20FAQ.md)
-[Terminology Cheatsheet](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Blockchain%20Terminology%20Cheatsheet.md)
-[Installation Guides](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Installation%20Guides.md)
-[Notes on Consensus Algorithms](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Notes%20on%20Different%20Consensus%20Algorithms.md)
-Additional guides on node creation, genesis block creation, and transactions on the blockchain can also be found in the [References](https://github.com/Santiago-Pedemonte/Private-Blockchains/tree/main/References) section of the repo.



# Blockchain
![introImage](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/Screenshots/blockchain-use-cases.jpg)

A repository of private blockchains with different consensus algorithms and developed with the [Go Ethereum](https://geth.ethereum.org/) implementation.

## Index

- [How a Blockchain Works](https://github.com/Santiago-Pedemonte/Private-Blockchains#how-a-blockchain-works)
- [Features](https://github.com/Santiago-Pedemonte/Private-Blockchains#features)
- [How to use](https://github.com/Santiago-Pedemonte/Private-Blockchains#how-to-use)
- [Resources](https://github.com/Santiago-Pedemonte/Private-Blockchains#resources)

<details><summary> How a Blockchain Works </summary>
  
   <img class="fit-picture"
     src="https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/Screenshots/infoBlockchain.jpg"
     alt="What is a Blockchain">
  
   [Source: Bitpanda](https://www.bitpanda.com/academy/en/lessons/how-does-a-blockchain-work/)
</details>

## Features

### Network

Each network (blockchain) has had a genesis block generated and is fully functioning (transactions have been made successfully during testing). The relevant network Id, network name, and other specifications can be found in the appropriate 'Keys, etc....txt' file or on the `networkname.json` file (substituting networkname for the actual name of the network).

![Network Files](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/Screenshots/networkFilesSS.png)

The `networkname.json` file will look something like this:

![Network info](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/Screenshots/pownetConfigSS.png)

Below this 'network summary', you'll find the prefunded and precompiled accounts' public keys. The public keys for the nodes will be all the way at the bottom of this list.

So far, two different networks have been added with different consensus protocols (for more information on consensus protocols please refer to the [CP notes](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Notes%20on%20Different%20Consensus%20Algorithms.md)).

### Nodes

Each Blockchain contains two node files. These are full nodes that have already been initialized on the network- for more information on node creation and initialization, please refer to the [node guide](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Node%20Creation%20and%20Initialization.md).

The first and second nodes have been conveniently-named `firstNode` and `secondNode`, respectively. Each of these nodes had a personal account created at the same time they were generated. The key pair for accessing the nodes' wallets (in the appropriate network) can be found in the relevant `Keys, etc....txt` file. Likewise, when using [MyCrypto](https://mycrypto.com/), one can also use the keystore file located in each of the nodes' folders.

![Keys,etc...](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/Screenshots/keyEtcSS.png)
![Node Files](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/Screenshots/nodeFilesSS.png)

For more information on the MyCrypto app, please refer to the [installation guide](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Installation%20Guides.md#installing-mycrypto-desktop-app)

The commands for starting each of the nodes are also included in the `Keys, etc....txt` file. The only element that may change when hosting the blockchain on another local host is the enode- if so, simply copy and paste the first node's new enode:// address in the second node's start command.

![firstEnodeSS](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/Screenshots/firstEnodeSS.png)
![secondEnodeSS](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/Screenshots/secondEnodeSS.png)

Links to more detailed explanations of these in the [How to Use](https://github.com/Santiago-Pedemonte/Private-Blockchains#how-to-use) section below.

## How to use
**Note: Geth should already be installed prior to booting up and using the network. Please refer to the [install guide](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Installation%20Guides.md#installing-go-ethereum-tools)**

### Starting the nodes, ports, and connections:

For particular commands and/or a more comprehensive, step-by-step guide regarding startup of nodes on Blockchains with a particular consensus, please refer to the individual `README.md` inside each network's folder:
* [Proof of Work-How to use](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/Proof-of-Work%20Blockchain)
* [Proof of Authority-How to use](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/Proof-of-Authority%20Blockchain)

The start commands for the nodes are included in the `Keys, etc....txt` file and should be run from inside the `/Geth` folder.

### Adding the Custom Network to MyCrypto:


## Resources

-[Useful links](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Useful%20Links.md)\
-[Blockchain FAQs](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Blockchain%20FAQ.md)\
-[Terminology Cheatsheet](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Blockchain%20Terminology%20Cheatsheet.md)\
-[Installation Guides](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Installation%20Guides.md)\
-[Notes on Consensus Algorithms](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Notes%20on%20Different%20Consensus%20Algorithms.md)\
-Additional guides on [node creation](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Node%20Creation%20and%20Initialization.md), [genesis block creation](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Creating%20a%20Genesis%20Block.md), and [transactions](https://github.com/Santiago-Pedemonte/Private-Blockchains/blob/main/References/Transaction%20Guide.md) on the blockchain can also be found in the [References](https://github.com/Santiago-Pedemonte/Private-Blockchains/tree/main/References) section of the repo.


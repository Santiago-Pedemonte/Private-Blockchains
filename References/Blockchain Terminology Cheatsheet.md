## Terminologies

- Blockchain: A network of nodes or machines linked in a peer-to-peer fashion that facilitates transactions in a verifiable and permanent way. A blockchain network is also often called an open distributed ledger.

- Blockchain Node: A node is a single machine that contributes to the infrastructure of a blockchain network. Blockchains networks as a whole are composed of multiple nodes that are interconnected with each other and therefore exchange the latest blockchain data with each other so that each node is up-to-date with the latest verified transactions on the blockchain network.

- Mining: Blockchain mining is the process of adding verified transaction records to the current blockchain data; miners act as separate nodes that are paid a fee to verify blockchain transactions and do so by solving intense computations to finalize transactions.

- Wallet: A blockchain wallet is a digital wallet containing a public and private key that is used to not only store cryptocurrencies, but also conduct secure transactions amongst other users via wallet addresses (hashed version of a public key). It is imperative that the private key for a digital wallet be kept safe, as losing it will be prevent a user from accessing their funds (no other way for decryption).

- Hash: A hash value is a product of a function that converts an input of letters and numbers into an encrypted output of a fixed length. Hashing is one way to enable security during message transmission when the message is intended for a particular recipient only, ensuring that the message has not been tampered with, as doing so would generate a new hash value different from the originating hash value.

- Digital Signature: A digital signature is a numerical value that is represented as a sequence of characters and is the product of ensuring the contents of a message have not been altered in transit (integrity), that the message was indeed sent by the sender (authentication), and that the sender cannot deny having sent the message (non-repudiation).

- Encryption: Encryption is the process in which a message is encoded in a format that cannot be read or understood by an external party lacking the necessary credentials.

- Symmetric Encryption: Symmetric encryption is the simplest type of encryption that uses only a single key (a private/secret key) to both encrypt and decrypt information. As a result, the parties communicating via symmetric encryption must exchange the secret key so that it can be used in the decryption process, which is a security disadvantage compared to asymmetric encryption.

- Asymmetric Encryption: Asymmetric encryption uses a key pair: a public and private key. As the name suggests, the public key is made freely available to anyone on the Internet while the private key is kept a secret by the end-user. Therefore, messages that are encrypted using the public key can only be decrypted using the associated private key, and messages that are encrypted using the private key can only be decrypted using the associated public key.

- A note on encryption types: Symmetric encryption is the oldest and best-known technique for encryption; however, because of its use of only a single key (the private/secret key), there is the potential for a breach in security when exchanging the private key between two parties, especially over a vast network such as the Internet with possible eavesdroppers. In contrast, due to the use of a key pair in asymmetric encryption (public and private key), the private key is never exchanged and therefore is kept a secret at all times. Though as a result of the use of a key pair, asymmetric encryption is slower than symmetric encryption due to the increased processing power used to encrypt and decrypt messages.

- Consensus Algorithm: A protocol used to verify the validity of transactions on a blockchain network. Due to the decentralized nature of the blockchain network, there is no central authority and therefore nodes within the blockchain network must be able to verify such transactions with certainty.

- Proof of Authority: PoA is a reputation-based consensus algorithm in which the model relies on a limited number of block validators that act as moderators to verify the newest blocks and transactions.

- Proof of Work: PoW is an asset-based consensus algorithm in which the model relies on producing a piece of data which is both resource (computation) and time intensive, but allows for others to verify the validity of the transaction. This consensus algorithm directly relates to the blockchain mining concept in which miners solve intense computations to finalize transactions.

- Proof of Stake: PoS is a collateral-based consensus algorithm in which the model relies on transactional validators whom are selected based on the amount of Bitcoin or Ether they hold. When they validate transactions, they put up a stake of their own Bitcoin or Ether and are rewarded (proportional to their stake) when a new block or transaction is added to the blockchain.

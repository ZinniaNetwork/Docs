---
description: WELCOME TO ZINNIA
cover: ../.gitbook/assets/Banners (1).png
coverY: 0
---

# Navigator

**All the information collated by and committed to the Zinnia blockchain, such as block and transactional data, is accessible to anyone through our block explorer - Zinnia Navigator.**&#x20;

<mark style="background-color:orange;"></mark>

## What information does the Zinnia Navigator provide?

Public blockchains are designed to be transparent; Zinnia is no exception.

Block explorers act as the portal to obtain and view the information committed to the Zinnia blockchain. &#x20;

Below we are going to look at the different types of information accessible via Zinnia Navigator.&#x20;

## Block Data

The block height tells us the # number of the current block; it also tells us how many blocks have been created since Zinnia's inception, indicating the chain's length.

The block contains lots more critical information, and they are worth trying to familiarise yourself with.

As we mentioned before, blocks collate all transactions within a specific time frame, known as "Block time."&#x20;

Zinnia's block time, on average, is 30 seconds; however, this isn't a fixed time and fluctuates slightly based on a few different factors we will discuss later. &#x20;



Ok, so what extra data can we obtain from a block explorer?&#x20;

## **Basic Block Information**

**Size:** Block size (in bytes).

**Difficulty:** The difficulty of mining the block.

**Time Stamp:** The time the block was mined.

**Block Reward:** The amount of new Zinn minted.

**Miner Address:** The miner who found the block.

**Miner committed data:** – Any extra data the miner has included in the block.

**No Transactions:** The number of transactions included in the block.

## **Advanced Block Information**

**Hash:** The cryptographic hash identifying the block. &#x20;

**Nonce:** The value used to demonstrate the miner carried out proof-of-work.&#x20;

**Merkle Root:** The root of the Merkle tree is assigned a hash. This hash stores the entire state of the system.

**Sha3Orphan:** The parent hash of all orphan blocks.

**Parent Hash:** The block's hash came before the current block.

## **Orphan Blocks**

Orphan blocks occur when two miners create blocks at the same time. Only one block can be successful and known by the network.&#x20;

Orphan blocks are disregarded and not recognized by the network.

Zinnia Navigator provides the following information about orphan blocks:

**Time:** The time they occurred.

**Block Height:** The block height they were created.

**Miner Address:** The miner who created the orphan block.

****

## Transaction **Data**

### **Standard Transaction Information**&#x20;

**Transaction hash:** Hash of the submitted transaction.

**Status:** Indicates if the transaction is:&#x20;

* Pending.
* Failed.
* Successful.

**Block:** The block housing the transaction.

**Timestamp:** The time a miner mined the block.

**From:** The address of the account that sent the transaction.

**To:** The address of the recipient.

**Value:** The total #No of Zinn transferred.

**Transaction Fee:** The fee paid to use the network: (Held in Z-2122)



### **Advanced Transaction Information**

* **Nonce:** The value used to demonstrate the miner carried out proof-of-work.&#x20;
* **Nonce:** The value used to display the miner carried out proof-of-work.

# Bitcoin Blockchain Technology With Focus On FPGA Miners

### Abstract:

Bitcoin is decentralized payment system and the most famous cryptocurrency which has a peer-to-peer network that operates on a cryptographic protocol. Bitcoin does not rely on any centralized entity like banks or governments to ensure the system reliability. Users send and receive bitcoins (the units of currency), directly from person to person, by broadcasting digitally signed messages to the network. Transactions are recorded into a distributed, replicated public database known as the blockchain, with consensus achieved by a proof-of-work system called mining, where miners are rearward for computing power spent to support the network. In this paper we discuss the bitcoin technology, process of Bitcoin mining, and mining hardware with focus on FPGA miners.

#### Research Aim:

The main objectives of this project are as follows.

- Learn about the bitcoin network and payment system
- Study cryptography basics, Cryptographic Hash Functions properties, data structures based on cryptography (Blockchain), and digital signature.
- Analyze bitcoin mining algorithm and SHA-256
- Study mining concept and compare the advantages of implementing bitcoin mining in different hardware.
- Learn about what FPGA is, describe the architecture of it, and how is the usage and applications of it in bitcoin mining compare to other hardware.

#### Keywords:

Cryptocurrency, Bitcoin, FPGA, Cryptography, Hash function, SHA256, Blockchain, Digital signature, Mining.

.

---

.

## Table of Contents

#### [1-INTRODUCTION](chapters/Chapter 1 'Introduction'.md)

#### [2-CRYPTOGRAPHY](chapters/Chapter 2 'Cryptography'.md)

    2.1-Cryptographic Hash Functions
        Property 1: Collision Resistance
        Property 2: Hiding - Preimage resistance (one wayness)
        Property 3: Puzzle Friendliness - Target Collision Resistance
        SHA-256
    2.2-HASH POINTERS AND DATA STRUCTURES
        Hash pointer
        Block chain
        Merkle tree
    2.3-DIGITAL SIGNATURES
        Digital signature scheme
        ECDSA
        Public Keys as Identities

#### [3-BITCOIN MECHANISM & NETWORK](chapters/Chapter 3 'Bitcoin Mechanism & Network'.md)

    3.1-Bitcoin in use
    3.2-Bitcoin Concepts
        Transactions
        Timestamp Server
        Proof-of-Work
        Bitcoin Mining in summary
        Consensus mechanism
        Privacy
    3.3-Bitcoin blockchain data structure
        Block Header

#### [4-BITCOIN MINING](chapters/Chapter 4 'Bitcoin Mining'.md)

    4.1-The task of Bitcoin miners
        Finding a valid block
        Difficulty
    4.2-Mining Hardware
        A closer look at SHA‐256
        CPU mining
    GPU mining
    FPGA mining
    ASIC mining

#### [5-FPGA](chapters/Chapter 5 'FPGA'.md)

    5.1-Introduction
        Requirement of FPGAs
    5.2-Architecture and Structure of FPGA
        Internal Architecture of LUT
        Routing Architecture - switch matrix
        Additional Elements In Contemporary FPGA Architectures
    5.3-FPGA Programming
        HDL & Synthesize
        Translate process
        Map process
        Place and Route
        Device Programming - Bitstream Generation
    5.4-FPGAs Vs ASICs
    5.5-FPGA As Bitcoin Miner
        FPGA mining versus GPU and CPU and ASIC mining
        Profitability of FPGA mining

#### [6-CONCLUSION](chapters/Chapter 6 'Conclusion'.md)

    Professional mining
        Mining hardware evolution: Similarities to gold mining
        A look to the future - The cycle repeats itself


---



[MOHAMMAD NIKNAM](https://github.com/MohammadNiknam17)
2021-2022

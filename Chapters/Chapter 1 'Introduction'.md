# 1.INTRODUCTION

Bitcoin, \"A Peer-to-Peer Electronic Cash System\"[^1], is unlike anything the world has seen before. By providing fast, inexpensive, international money transfer, it has the potential to revolutionize both the modern-day concept of money and commerce.

Bitcoin is a peer-to-peer[^2] digital currency based on public key cryptography. It started as a free software project and a paper published by Satoshi Nakamoto[^3] in 2009. Nakamoto, designed a system of online value transfer that supports a promising Internet currency. He introduced bitcoin as a version of electronic cash that would allow payments to be Sent from one party to another without going through a financial institution.

Traditionally, financial institutions, such as banks, are trusted to store and protect a customer’s currency. The bank will handle the transfer of money between its customers and clients, but there are several disadvantages in this trust-based model. Electronic transfers between banks can be costly since there is usually a transaction fee, they can be slow taking several days to complete, and transfers cannot be made anonymously and completely non-reversible transactions are not really possible, since financial institutions cannot avoid mediating disputes. The cost of mediation increases transaction costs. But no mechanism exists to make payments over a communications channel without a trusted party.

What is needed is an electronic payment system based on cryptographic proof instead of trust. Bitcoin is a system of owning and transferring currency that omits these trusted third parties, allowing any two willing parties to transact directly with each other without the need for a trusted third party. And instead, Satoshi propose a solution to the double-spending[^4] problem using a peer-to-peer distributed Timestamp server to generate computational proof of the chronological order of transactions.

Bitcoin is made possible by a combination of software and network technologies. A program called the Bitcoin client simultaneously manages and helps you spend bitcoins. This program maintains a long ledger called the blockchain that holds every transaction confirmed by the Bitcoin network.

The Bitcoin network, consisting of thousands of machines running the Bitcoin software, has two main tasks to accomplish. One is relaying transaction information and the second is verifying those transactions to ensure the same bitcoins cannot be spent twice.

The first task is accomplished easily due to the fact that the Bitcoin network is operated as a peer-to-peer network. After all, sharing data is easy. By operating on many nodes across the globe, the network ensures it will operate as long as it provides a useful service, and the system is secure as long as honest nodes collectively control more CPU power than any cooperating group of attacker nodes.

The second task is a bit more complicated and is solved through what I consider to be Bitcoin\'s key innovation. This development, a process called mining, is carried out by computers running mining software.

---
By [Mohammad Niknam](https://github.com/MohammadNiknam17)

[^1]: *This phrase is come from title of original bitcoin whitepaper by Nakamoto in 2009.*
    
[^2]: *P2P - Peer-to-peer refers to systems that work like an organized collective by allowing each individual to interact directly with the others. In the case of Bitcoin, the network is built in such a way that each user is broadcasting the transactions of other users. And, crucially, no bank is required as a third party.*
    
[^3]: *Satoshi Nakamoto -- the creator of Bitcoin and the author of the original Bitcoin whitepaper and code. His real identity is unknown to the world.*
    
[^4]: *Double Spend - If a malicious user tries to spend their bitcoins with two different recipients at the same time, this is double spending. Bitcoin mining and the block chain are there to create a consensus on the network about which of the two transactions will confirm and be considered valid.*

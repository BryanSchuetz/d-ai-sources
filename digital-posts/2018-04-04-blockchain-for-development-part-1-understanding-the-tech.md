---
title: 'Blockchain for Development Part 1: Understanding the Tech'
date: 2018-04-04 11:20:00 -04:00
tags:
- Digital Financial Services
- Blockchain Series
Author: Trevor Olexy
social-image: "/uploads/Figure.png"
thumbnail: "/uploads/Figure.png"
---

Bitcoin has launched the term “blockchain” into the world’s tech vernacular. Unfortunately for blockchain as a technology and a theory, it is often, for better or worse, synonymized with Bitcoin. Because of this, the ideas of public, transparent, and unchangeable information immediately come to mind as soon as someone mentions blockchain. While this is true for Bitcoin, this is not necessarily the case for all blockchains. 

<!--more-->

There is a significant gap in education when it comes to the fundamental core functionality and abilities of a blockchain. Notice the wording there; that it is ‘a’ blockchain, not ‘the’ blockchain. Bitcoin uses blockchain technology (sometimes called distributed ledger technology) in a specific, financial way, but there are myriad other ways in which to implement blockchain. 

In Part 1 of this two-part series, I will present some high-level background to how the technology works. Part 2 will then provide examples where blockchain could be appropriate in an international development context and instances where its use may be a bit forced, symptomatic of a larger desire to fit a square technology into a round programmatic hole. 

## Blockchain, Simply

Briefly, a blockchain allows two parties to share or process data securely using a network of computers that process the information in the same way at the same time, achieving consensus, and committing the transaction or data to the blockchain. That is a simplification if there ever was one, but a blockchain is similar to a database in that it is a way to store information and can do so securely and anonymously.  

There are numerous resources available ([here](https://www.ibm.com/blogs/blockchain/2017/12/blockchain-security-what-keeps-your-transaction-data-safe/), [here](http://mitsloan.mit.edu/newsroom/articles/blockchain-explained/), and [here](https://marmelab.com/blog/2016/04/28/blockchain-for-web-developers-the-theory.html)) that provide a detailed technical readout of blockchain technology, many of which I referenced as I began my journey constructing blockchains and distributed applications from scratch using the Ethereum framework. Ethereum is a cryptocurrency that uses a different underlying structure than Bitcoin, but the same blockchain principles. It is also written in its own programming language, allowing developers to build custom applications that can be run on the blockchain network.

## How it Works

Blockchains are composed of bundles (blocks) of information or transactions that are connected (chained) using cryptography. If I were to take this digital article you are reading at this moment and encrypt it using current standard cryptographic algorithms, the encrypted output (known as a “hash”—complex alpha-numeric string) would always be the same. If I added one letter, changed one character, even changed the capitalization of a letter, the encryption output would be different. When each new block is created and subsequently encrypted, it includes the encryption (hash) of the previous block of information. This is how blocks are “chained” together. You can see this normal operation in the figure below between blocks 20 and 22. Block 23 illustrates what happens when an attempt to change the blockchain history occurs. If some nefarious actor were to attempt to alter the information in any previous block, the cryptographic hash of that block would change, creating a conflict with every block created since. 

![Figure.png](/uploads/Figure.png)

This is how the blockchain ensures that once data has been committed to the transaction history that information cannot be changed and can do so without having to compare large amounts of information. 

Small programs can be written and stored on the blockchain that only run when certain conditions are met, like payments made only on a certain day, or only when two parties agree to certain conditions. These programs are called smart contracts because they don’t involve intermediaries like banks or lawyers. Using smart contracts, money or digital facsimiles of property can be automatically transferred between digital “wallets” and verified by the entire network. Each user on the blockchain controls a digital wallet that contains the balance of Bitcoin, other cryptocurrency, or digital mirrors of physical assets that they own in the material world. It is important to note that these wallets are not restricted to holding only money, but can store information as well. 

The complete blockchain is held on many nodes throughout the network. These nodes verify transactions and keep the blockchain active. Individual computers (or mobile phones) or users can connect to these nodes to transfer goods, services, or information. The distributed networking of a blockchain is quite complex, so I will leave it there for now and you can read through [this article](https://hackernoon.com/lets-talk-about-bitcoin-nodes-e9502193198c) for more information. 

## Blockchain Detangled from Bitcoin

Since blockchain is so linked to Bitcoin in terminology and understanding, I will discuss three oft-mentioned characteristics of blockchain technology and theory to give you a better idea of what all these blockchain terms really mean in use across different applications and implementations. Think of this more as clarification rather than myth-busting.   

**1. “Blockchains are secure and immutable.”**

Well yes, mostly. I won’t go into the math or other circumstances around majority control of the blockchain network or quantum computing, but for most intents and purposes it is true that you cannot change the blockchain history. It is extremely computationally difficult and resource prohibitive to alter the information stored in a blockchain. This does not mean it is impossible, but really it is too difficult and would require too many computers to achieve. 

**2. “Blockchains are public, transparent, and anonymous.”**

While Bitcoin does allow all users to remain anonymous and audit the transaction history stored on the blockchain, this is merely the method Bitcoin has used to implement its blockchain. Private blockchain networks exist in which access to the network is only provided to a select group of individuals or businesses. These rely on the same technology as Bitcoin, but permissions can be set so that one entity can control visibility of their information or transactions on the network. For example, company A can send money to company B, allow company C (oversight regulator for instance) to see the transaction, but disallow viewing by company D (a competitor). This example demonstrates the usefulness of blockchain in securing and selectively controlling access to information that is stored unchanged in the history of the blockchain. Generally, a private blockchain is likely the most appropriate implementation in a development context.

**3. “Blockchain is only used for financial transactions.”**

While this is again tied to the Bitcoin implementation, it is important to note that blockchains can store any information. Some people have even tried to store images on the blockchain, though in the Bitcoin and Ethereum networks this can become very expensive as each transaction does have an associated cost. Just one of the many potential uses outside of financial transactions could be private storage of vaccination records.

You can now unbuckle your safety harnesses and step back from the blockchain ride. There is a lot of background information that goes into understanding blockchain at a technical level, from public-private key security certificates and programming, to distributed computing, networking, and economics. Brave pioneers wanted.
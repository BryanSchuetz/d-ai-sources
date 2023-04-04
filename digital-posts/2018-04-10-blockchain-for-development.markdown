---
title: 'Blockchain for Development Part 2: Implementation Considerations'
date: 2018-04-10 10:20:00 -04:00
tags:
- Agriculture
- Innovation
- Global Health
- Blockchain Series
Author: Trevor Olexy
social-image: "/uploads/Blockchain_Illustration_3.jpg"
thumbnail: "/uploads/Blockchain_Illustration_3.jpg"
---

As discussed in Part 1 of this two-part post on blockchain, "[Understanding the Tech](/blockchain-for-development-part-1-understanding-the-tech.html)," the blockchain hype is pervasive in international development these days. It is my view that blockchain does not deserve the “Swiss army knife of new technology” label that has been thrust upon it. While blockchain is exciting and potentially very useful, appropriate application of the tech can be evasive. If you need a quick and simple run down of blockchain, check out [Part 1](/blockchain-for-development-part-1-understanding-the-tech.html). Here I will give you a glimpse of some of the potential uses for blockchain in global development programming, and some of the challenges.

<!--more-->

## Potential Use

### Supply Chain

Currently, there are several companies ([IBM](https://www.ibm.com/blockchain/supply-chain/), [Provenance](https://www.provenance.org/), and others) implementing supply chain systems that are built on top of blockchain technology stacks. Value chain tracking and verification is one of the most promising areas for blockchain to operate and has potential applications for smallholder farmers and farmer cooperatives. Since one of the primary advantages of blockchain technology is the removal of a necessary trusted third party to handle financial transactions, there’s a natural fit of blockchain in supply chain management or asset/goods/materials tracking. Digital representations of goods/assets and money can be automatically transferred between parties when both parties agree to predetermined conditions or product quality. If at some point in the physical world an asset is not as recorded on the blockchain, the blockchain can be audited and the source of the discrepancy can be isolated and investigated. This also opens avenues for the use sensors and the internet of things to track a product’s mass, temperature, or humidity, helping to ensure product quality from production to consumption. 

### Medical Records

If I asked you where your medical records are at this very moment, unless you have been to the same doctor for most of your life or are part of a network with a well-established electronic medical record system, you may be unable to answer with confidence. Medical records can be stored securely, privately, and permanently in a private, permissioned blockchain. In this implementation, the owner of the record (the patient) can grant or revoke access to their medical records when and to whom they see fit. This is important because it maintains privacy; can become a system of record for patients with little confidence in their medical history; and returns control of personal data to the patient. Access to medical professionals can be infrequent in developing countries and although there are many organizations pushing to digitize medial records, this effort is often highly localized and can be difficult to implement nationally. Although there may be a heavy upfront lift in this case, blockchains can be considered somewhat autonomous upon creation, thus simultaneously increasing data integrity and reducing maintenance resources for large stores of patient data. There are not many (if any complete) examples of this yet, but check out MIT’s [prototype ](https://medium.com/mit-media-lab-digital-currency-initiative/medrec-electronic-medical-records-on-the-blockchain-c2d7e1bc7d09) electronic medical record system.

![Blockchain Blog_Part2_picSMALL2.jpg](/uploads/Blockchain%20Blog_Part2_picSMALL2.jpg)

### Elections

Election tracking and verification is an interesting potential implementation of blockchain, particularly in countries where elections can be fraught with election officials and politicians of questionable integrity. The blockchain can track a constituent’s selections on a ballot, ownership of that ballot, aggregate data from polling stations, transfer the vote counts to the central election commission, and could do this all with little human intervention, or rather, interference. In a world where voting systems are constantly under intense scrutiny and doubt, securing the vote is vastly important to maintaining integrity of democratic systems. There are already companies doing their best to get the word out about the benefits of using blockchain for voting and the company [Voatz](https://voatz.com/) has even utilized the platform at the 2016 Massachusetts Democratic Party State Convention.

## Challenges

### Technology Saturation

In a development context, the technological hurdles for projects with a digital component can often seem insurmountable, hardly a nurturing environment for a new technology that relies on distributed computing and a perpetually live network. Desktop computers and laptops are still not ubiquitous the world over due to any number of challenges from lack of funding and lack of regular access to electricity, to gaps in literacy. For these reasons, mobile implementations of blockchain technology have the potential to make their way (albeit conscientiously) into the international development space. For example, a farmer with a mobile device could connect to a blockchain, submit a transaction such as the sale of produce to a wholesaler or exporter, and receive the money promptly in their digital wallet. This begs the question though, how wide is mobile network or data coverage where these farmers live? Coverage and reliability gaps can quickly restrict usage of a blockchain to areas with consistent data signal or a central hub with wi-fi.

### Data sovereignty

By nature, data in blockchains are stored on multiple nodes which are used to validate transactions and provide redundancy. In the case of larger blockchain implementations such as Ethereum and Bitcoin, there are thousands of nodes across the world. However, in the case of a blockchain administered by a central government that is concerned about the physical location of sensitive data, this may be unacceptable. There are cases in which central governments refuse to use Amazon Web Services to store data because they do not want it to travel beyond the sovereign boundaries of their countries. Blockchain nodes can be restricted to use within a country’s boundary, but this raises questions about the true distributed nature of blockchain. In these cases, centralized, redundant, and secure servers may be the most appropriate use of tech.

### Data Privacy

Another important aspect of blockchain implementation is the sensitivity of the data stored. In this instance, we want the opposite of the transparent Bitcoin: we need a selectively opaque blockchain. Take the example of a blockchain program (distributed application or *DApp*) that tracks a patient’s vaccination history. This data is sensitive and could cause harm to an individual if viewed by a malicious party. Careful consideration must be given to who will be in control of the network and especially to how it is created. Proper permissions and control rules must be set to keep control in the hands of the patient rather than those who maintain the network infrastructure. Should a not-so-well-intentioned individual or group gain control of the government and thus the vaccine record blockchain, and if this data were public as in Bitcoin, this group could potentially target patients or their families based on their medical history. Blockchain user identity is generally pseudonymous and difficult, if not impossible, to track, but in this case where identity may be stored (although encrypted) in the blockchain, it may be possible to extort information from doctors or hospitals after information access is granted by the patient.

Blockchain is still relatively new, generally misunderstood, and simultaneously simple and complicated. It is not appropriate for every situation. Simple databases provide similar functionality, and perhaps that is all that is needed in many cases. Throwing new technology at old problems is not always the best way to go. However, the world always needs pioneers to find solutions by different means. Blockchain developers and implementers looking to use distributed ledger technology to help solve problems need to be careful not to apply the theory for the sake of the tech, but for the improvement of processes and systems.

More good reading, if you haven’t had enough already, can be found [here](https://eng.paxos.com/blockchain-separating-hype-from-substance).
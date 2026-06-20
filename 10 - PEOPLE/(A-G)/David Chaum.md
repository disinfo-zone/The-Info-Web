---
category: "Technologists"
tags:
  - Person
  - DavidChaum
  - Cryptography
  - DigitalCash
  - DigiCash
  - Privacy
  - Cryptocurrency
alias:
  - David Lee Chaum
  - David Chaum
summary: "David Chaum is the American cryptographer who invented anonymous digital cash, devised the mix network and the blind signature, wrote a 1982 dissertation that anticipated the blockchain, and built the DigiCash eCash system whose 1998 bankruptcy left the cypherpunks to pursue trustless money."
born: 1955
location: "United States"
created: 2026-06-20
updated: 2026-06-20
---

David Lee Chaum (born 1955) is an American cryptographer who founded the field of anonymous digital cash and privacy-preserving cryptography. In a series of papers beginning in 1981 he introduced the mix network for untraceable communication, the blind signature for untraceable payment, and the dining cryptographers protocol for unconditional sender anonymity, and his 1982 doctoral dissertation set out a system that anticipated much of the later blockchain. Through his company [[DigiCash]] he built [[eCash]], the first working electronic-money system, which depended on a bank as a trusted issuer and went bankrupt in 1998. The [[Cypherpunks]] built directly on his work, and the trustless designs that became [[Bitcoin]] were in part an effort to remove the central issuer his system required.[^1][^2]

### Mix Networks and the Dining Cryptographers

Chaum earned a doctorate in computer science from the [[University of California, Berkeley]], and taught there and at [[New York University]] before moving his research to the [[Netherlands]]. His 1981 paper "Untraceable Electronic Mail, Return Addresses, and Digital Pseudonyms," published in Communications of the ACM, introduced the mix network, a chain of relay servers each of which receives a batch of encrypted messages, decrypts one layer, shuffles the order, and forwards them, so that no single relay and no outside observer can link a message entering the chain to one leaving it. The design is the conceptual ancestor of later anonymity systems including the onion-routing network Tor.[^3][^4]

In 1988 Chaum published "The Dining Cryptographers Problem: Unconditional Sender and Recipient Untraceability" in the Journal of Cryptology, which posed a puzzle: three cryptographers at dinner want to learn whether one of them paid the bill or whether their employer did, without revealing which of them paid. The protocol he derived, in which each participant shares a secret coin flip with a neighbor and announces the parity, lets the group compute whether any member sent a message while hiding which one did, with anonymity that holds even against an adversary with unlimited computing power. The construction, known as a DC-net, became a foundation of research into anonymous communication.[^5][^6]

### Blind Signatures

Chaum presented "Blind Signatures for Untraceable Payments" at the CRYPTO '82 conference, published in the proceedings in 1983, building on the idea he had set out in his 1982 dissertation. A blind signature lets a signer certify a message without seeing its contents. In Chaum's payment scheme a customer generates a digital banknote with a serial number, multiplies it by a random blinding factor so the bank cannot read it, and sends the blinded value to the bank; the bank signs it and debits the customer's account, the customer divides out the blinding factor to recover a valid signed note, and when a merchant later deposits that note the bank sees its serial number for the first time and cannot connect it to the withdrawal.[^2][^7]

The result was electronic money that was anonymous like physical cash yet unforgeable like a bank-signed instrument, since the bank's signature could not be reproduced without its private key and any attempt to spend the same note twice could be detected at deposit. The blind signature solved the central problem that had blocked anonymous digital payment, and it became the cryptographic core of every system Chaum built afterward. His 1985 paper "Security Without Identification: Transaction Systems to Make Big Brother Obsolete" extended the approach into a broader scheme of pseudonymous credentials.[^2][^8]

### The 1982 Dissertation

Chaum's Berkeley dissertation, "Computer Systems Established, Maintained, and Trusted by Mutually Suspicious Groups," completed in 1982, described how a group of parties who do not trust one another could jointly operate a record-keeping system whose integrity none of them could subvert. The design specified a data structure in which entries were chained together by cryptographic references and replicated across the participants, so that the history could be audited and could not be altered after the fact without detection, and it included the code to implement the protocol.[^9][^10]

Commentators who later compared the dissertation to the 2008 Bitcoin white paper observed that it contained most of the structural elements of a blockchain, including a chained, tamper-evident ledger maintained by a set of mutually distrustful participants, and that the principal element it lacked was proof-of-work, the mechanism by which an open, permissionless network reaches consensus without a fixed membership. The Satoshi Nakamoto Institute republished the dissertation in its library as an antecedent of the blockchain.[^9][^10]

### DigiCash and eCash

Chaum founded DigiCash in [[Amsterdam]] in 1990, after his cryptographic group at the CWI research center, to commercialize anonymous electronic cash. Its product, eCash, used Chaum's blind signatures to issue digital coins that a customer withdrew from a participating bank, stored on a personal computer, and spent at merchants, with the bank unable to trace where its issued coins were spent. DigiCash also ran a free trial currency called CyberBucks. In October 1994 the company demonstrated the first live payment over the World Wide Web.[^1][^11]

Adoption never reached the scale the system needed. The Mark Twain Bank of St. Louis became the first licensee to offer eCash in 1995, followed in 1996 and afterward by [[Deutsche Bank]], [[Credit Suisse]], [[Bank Austria]], and a handful of others, but by 1998 the Mark Twain program had signed only about 300 merchants and 5,000 users. Reported negotiations with larger partners fell through, including a Visa investment and a Microsoft proposal to bundle eCash with Windows 95 over which Chaum and [[Bill Gates]] reportedly could not agree on terms. DigiCash filed for bankruptcy in November 1998. Chaum told Forbes the following year, "It was hard to get enough merchants to accept it, so that you could get enough consumers to use it, or vice versa."[^1][^12]

eCash differed fundamentally from the cryptocurrencies that followed. A customer's payment was anonymous, but a bank had to issue every coin, validate it, and maintain the account ledger, so the system could not operate without a trusted central institution and could be shut down by removing that institution. The proof-of-work currencies that the cypherpunks went on to design, beginning with [[Adam Back]]'s [[Hashcash]], [[Wei Dai]]'s b-money, and [[Hal Finney]]'s reusable proof-of-work and culminating in [[Satoshi Nakamoto]]'s Bitcoin, replaced Chaum's trusted issuer with an open network that mints and validates its own units, removing the single point of control that had defined eCash.[^13][^2]

### Later Work

After DigiCash, Chaum continued to work on cryptographic systems, concentrating heavily on verifiable election technology. He designed end-to-end verifiable voting schemes including Punchscan and the in-person system Scantegrity, which was used in a binding municipal election in Takoma Park, Maryland, in 2009. In the cryptocurrency era he returned to digital money with the Elixxir and Praxxis projects and the xx network, and he proposed eCash-style privacy designs for central bank digital currencies, work in which his original blind-signature approach reappeared decades after DigiCash.[^14][^4]

### Footnotes

[^1]: "The Genesis Files: How David Chaum's eCash Spawned a Cypherpunk Dream," *Bitcoin Magazine,* April 2018, on Chaum's biography, DigiCash founded 1990 in Amsterdam, eCash, the Mark Twain and Deutsche Bank licensees, the Visa and Microsoft talks, and the 1998 bankruptcy. https://bitcoinmagazine.com/culture/genesis-files-how-david-chaums-ecash-spawned-cypherpunk-dream
[^2]: Chaum, David. "Blind Signatures for Untraceable Payments," *Advances in Cryptology: Proceedings of CRYPTO '82,* Springer, 1983, pp. 199-203, on the blind-signature payment scheme. https://link.springer.com/chapter/10.1007/978-1-4757-0602-4_18
[^3]: Chaum, David. "Untraceable Electronic Mail, Return Addresses, and Digital Pseudonyms," *Communications of the ACM,* vol. 24, no. 2, February 1981, on the mix network. https://dl.acm.org/doi/10.1145/358549.358563
[^4]: "David Lee Chaum: The Pioneer of Digital Anonymity," *GNcrypto,* on the Berkeley doctorate, the mix network as ancestor of Tor, and his later election and currency work. https://www.gncrypto.news/news/david-lee-chaum-the-pioneer-of-digital-anonymity/
[^5]: Chaum, David. "The Dining Cryptographers Problem: Unconditional Sender and Recipient Untraceability," *Journal of Cryptology,* vol. 1, no. 1, 1988, pp. 65-75. https://chaum.com/wp-content/uploads/2022/01/chaum-dc.pdf
[^6]: "The Dining Cryptographers Problem," *Futility Closet,* on the 1988 protocol and DC-nets. https://www.futilitycloset.com/2018/10/03/the-dining-cryptographers-problem/
[^7]: "Blind Signatures for Untraceable Payments," *Springer Nature Link,* citation record for the CRYPTO '82 paper published 1983. https://link.springer.com/chapter/10.1007/978-1-4757-0602-4_18
[^8]: Chaum, David. "Security Without Identification: Transaction Systems to Make Big Brother Obsolete," *Communications of the ACM,* vol. 28, no. 10, October 1985, on pseudonymous credentials. https://dl.acm.org/doi/10.1145/4372.4373
[^9]: Chaum, David. "Computer Systems Established, Maintained, and Trusted by Mutually Suspicious Groups," University of California, Berkeley, June 1982, on the chained, replicated, tamper-evident record maintained by mutually distrustful parties. https://nakamotoinstitute.org/library/computer-systems-by-mutually-suspicious-groups/
[^10]: "Computer Systems Established, Maintained, and Trusted by Mutually Suspicious Groups," Satoshi Nakamoto Institute library entry, characterizing the 1982 dissertation as containing the elements of a blockchain except proof-of-work. https://nakamotoinstitute.org/library/computer-systems-by-mutually-suspicious-groups/
[^11]: "DigiCash Idea Finds New Life in More Flexible eCash," *American Banker,* on the eCash system, the bank trials, and the demonstration of web payment. https://www.americanbanker.com/news/digicash-idea-finds-new-life-in-more-flexible-ecash
[^12]: "'82: The Birth of Digital Cash," Till Antonio Mahler, *blockwhat?,* on the Mark Twain Bank, the limited adoption figures, the Microsoft and Visa negotiations, and the November 1998 bankruptcy. https://medium.com/blockwhat/82-the-birth-of-digital-cash-ea08b53379d8
[^13]: "The Extropian Roots of Bitcoin," *CCN,* on the digital-cash precursors that removed the trusted issuer. https://www.ccn.com/extropian-roots-bitcoin/
[^14]: "Understanding David Chaum: Pioneer of Digital Privacy and Cryptography," *CoinStats,* on Scantegrity, the Takoma Park election, and the xx network. https://coinstats.app/news/0e7c5927f0be24286a2140761b3fb115289bd6e241174487562250ab1aef2645_Understanding-David-Chaum-Pioneer-of-Digital-Privacy-and-Cryptography/

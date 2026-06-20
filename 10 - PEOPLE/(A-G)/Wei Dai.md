---
category: "Technologists"
tags:
  - Person
  - WeiDai
  - Cryptography
  - Cypherpunks
  - DigitalCash
  - Bitcoin
  - Rationalism
alias:
  - Wei Dai
summary: "Wei Dai is a computer engineer who proposed the b-money digital-cash scheme cited in the Bitcoin white paper, created the Crypto++ library, and posts in the rationalist community."
born: 1976
location: "United States"
created: 2026-06-19
updated: 2026-06-19
---

Wei Dai is a computer engineer and cryptographer associated with the [[Cypherpunks]] movement who proposed "b-money," an early scheme for anonymous, government-resistant digital money that [[Satoshi Nakamoto]] cited as the first reference in the [[Bitcoin]] white paper. He created the Crypto++ open-source cryptography library and is an active participant in the [[Rationalist Community|rationalist community]] around [[LessWrong]].[^1][^2]

### B-money

Born in 1976 and educated in computer science with a mathematics minor at the [[University of Washington]], Dai published the b-money proposal on the cypherpunks mailing list in November 1998. It opened by crediting [[Timothy May]]'s crypto-anarchy, in which "the government is not temporarily destroyed but permanently forbidden and permanently unnecessary," and described "a scheme for a group of untraceable digital pseudonyms to pay each other with money and to enforce contracts amongst themselves without outside help."[^1][^3]

The proposal set out two protocols. In the first, every participant kept a separate copy of how much money belonged to each pseudonym, and money was created by broadcasting the solution to "a previously unsolved computational problem," with the number of units minted equal to the cost of the computing effort measured against a standard basket of commodities. Recognizing that universal broadcast was impractical, Dai sketched a second protocol in which a subset of participants, the "servers," maintained the accounts on a Usenet-style broadcast channel and each deposited money in a special account to be forfeited as a fine on proof of misconduct, a bonded-validator structure that anticipated later proof-of-stake systems.[^3][^6]

### Citation in the Bitcoin White Paper

B-money appears as the first numbered reference in Satoshi Nakamoto's 2008 paper "Bitcoin: A Peer-to-Peer Electronic Cash System." Nakamoto first emailed Dai on August 22, 2008, writing, "I was very interested to read your b-money page," explaining that he was preparing "a paper that expands on your ideas into a complete working system," and that [[Adam Back]] of hashcash.org "noticed the similarities and pointed me to your site." Nakamoto asked for the year of publication so he could cite it, and Dai replied that b-money had been announced on the cypherpunks list in 1998.[^2][^4]

Nakamoto wrote to Dai again on January 10, 2009, the day after releasing the Bitcoin software, saying it "achieves nearly all the goals you set out to solve in your b-money paper" through a system "entirely decentralized, without any server or trusted parties." Dai has said the creator did not actually read his proposal before independently reinventing the idea, learning of it and crediting him only afterward, and that he believes Nakamoto arrived at the concept independently. The smallest unit of ether on [[Ethereum]], the "wei," equal to one quintillionth of an ether, is named after Dai.[^4][^6]

### Crypto++ and the Rationalist Community

Dai released the first version of his Crypto++ open-source C++ cryptography library in June 1995 and worked as a programmer at the firm TerraSciences and then in Microsoft's cryptography research group, where he co-proposed the VMAC authentication algorithm and held cryptography patents, before turning the library over to the community in 2015.[^1][^7]

On LessWrong, the rationalist forum founded by [[Eliezer Yudkowsky]], Dai introduced updateless decision theory in his August 2009 post "Towards a New Decision Theory," a framework treating the decision-maker as an algorithm that does not update on observations, which resolves Newcomb's problem and counterfactual mugging and fed into the functional decision theory later developed at the [[Machine Intelligence Research Institute|MIRI]]. He is a pessimistic voice on artificial-intelligence safety, arguing that problems in metaethics and metaphilosophy should be solved before building artificial general intelligence, which places him within the same [[Extropianism|extropian]]-descended intellectual milieu that produced [[Hal Finney]] and [[Nick Szabo]].[^5][^8]

### Footnotes

[^1]: "Cypherpunks Write Code: Wei Dai and B-money," *Medium,* on Dai's biography, b-money, Crypto++, and LessWrong activity. https://medium.com/@Carrsos1/cypherpunks-write-code-wei-dai-and-b-money-or-a-coin-before-bitcoin-8bf5836bfb36
[^2]: Nakamoto, Satoshi. "Bitcoin: A Peer-to-Peer Electronic Cash System," 2008, citing Wei Dai's b-money. https://bitcoin.org/bitcoin.pdf
[^3]: Dai, Wei. "b-money," 1998. http://www.weidai.com/bmoney.txt
[^4]: "Wei Dai/Satoshi Nakamoto 2009 Bitcoin emails," Gwern.net, on the 2008 correspondence and Back pointing Nakamoto to b-money. https://gwern.net/doc/bitcoin/2008-nakamoto
[^5]: "The Extropian Roots of Bitcoin," *CCN,* on the extropian and cypherpunk overlap of Dai, Finney, and Szabo. https://www.ccn.com/extropian-roots-bitcoin/
[^6]: Dai, Wei. "b-money," 1998, on the two protocols, proof-of-work issuance, and the bonded servers. https://nakamotoinstitute.org/library/b-money/ "Satoshi Nakamoto emails to Wei Dai, 2008-2009," Gwern.net, on the August 22, 2008 and January 10, 2009 messages. https://gwern.net/doc/bitcoin/2008-nakamoto
[^7]: Crypto++ Library, weidai11/cryptopp, GitHub, on the June 1995 first release and the library's history. https://github.com/weidai11/cryptopp
[^8]: Dai, Wei. "Towards a New Decision Theory," LessWrong, August 13, 2009. https://www.lesswrong.com/posts/de3xjFaACCAk6imzv/towards-a-new-decision-theory

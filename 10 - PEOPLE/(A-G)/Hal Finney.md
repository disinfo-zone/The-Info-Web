---
category: "Technologists"
tags:
  - Person
  - HalFinney
  - Cryptography
  - Cypherpunks
  - Bitcoin
  - Cryonics
  - Extropianism
alias:
  - Harold Thomas Finney II
  - Hal Finney
summary: "Hal Finney was a cryptographer who developed Pretty Good Privacy and reusable proof-of-work, received the first Bitcoin transaction from Satoshi Nakamoto, and was cryopreserved by Alcor after his death from ALS."
born: 1956-05-04
died: 2014-08-28
location: "Santa Barbara, California"
created: 2026-06-19
updated: 2026-06-19
---

Harold Thomas Finney II (1956 to 2014), known as Hal Finney, was an American cryptographer and software developer who worked on [[Pretty Good Privacy]], created the first reusable proof-of-work system, and received the first [[Bitcoin]] transaction sent by [[Satoshi Nakamoto]]. He was a participant in the [[Cypherpunks]] movement and the [[Extropianism|extropian]] community, and on his death from amyotrophic lateral sclerosis he was cryopreserved by the [[Alcor Life Extension Foundation]].[^1][^2]

### Cryptography and PGP

Finney graduated from the California Institute of Technology in 1979 and joined APh Technological Consulting, the firm Mattel contracted to develop the Intellivision, where he programmed the console game Space Battle and its Atari 2600 port Space Attack, as well as Astroblast, the 2600 port of Astrosmash. He began volunteering on [[Phil Zimmermann]]'s Pretty Good Privacy in 1991, became a central contributor to PGP 2.0, and when the federal investigation into Zimmermann closed in 1996 Zimmermann hired him as an employee.[^1][^2][^8]

Finney ran one of the early anonymous remailers, servers that stripped routing information so that a message could not be traced to its sender, and he was a frequent contributor to the cypherpunks list, where he introduced the idea of digital cash to the overlapping extropian community. He continued working on PGP under Zimmermann until ALS forced his retirement in 2011, by which point PGP had become the standard tool for encrypting email and the federal effort to suppress it had collapsed.[^3][^8]

### Reusable Proof-of-Work

Finney announced RPOW on August 15, 2004, a reusable proof-of-work system that took an [[Adam Back]] Hashcash token as input and returned an RSA-signed token that could be handed from person to person and exchanged for a fresh token at each step, so that the same proof of work could circulate while each underlying token was spent only once. He described the result as "as rare and 'valuable' as the hashcash that was used to create them," with no way to inflate the supply.[^3][^4]

RPOW ran on an IBM 4758 PCI cryptographic coprocessor, a tamper-responding device validated to FIPS 140 Level 4 whose onboard key never left the card and was cleared on any change to the running software. The card issued cryptographically signed attestations of its own software configuration, so users worldwide could verify in real time that the server held no back door and would mint a token only against a token of equal value. RPOW was a direct technical precursor to the proof-of-work scheme that Satoshi Nakamoto later used in Bitcoin, which replaced the trusted hardware with a decentralized blockchain.[^9][^10]

### Bitcoin

Finney was among the first people to engage with Bitcoin after Nakamoto released the software. He posted "Running bitcoin" in January 2009, and on 12 January 2009 he received the first Bitcoin transaction sent by Nakamoto, ten coins recorded in block 170, after which he exchanged emails with Nakamoto reporting bugs. In his 2013 forum essay "Bitcoin and me," written after he was largely paralyzed by ALS, Finney recounted his cryptographic career, his early mining of Bitcoin, and that he had moved his coins into an offline wallet so they might be "worth something to my heirs."[^1][^5][^6]

The speculation that Finney was Satoshi intensified in March 2014 when Leah McGrath Goodman's Newsweek cover story named Dorian Prentice Satoshi Nakamoto of Temple City, California, the same town where Finney had lived for about a decade. Andy Greenberg investigated Finney directly for Forbes, commissioning stylometric analysis from Juola and Associates that found his writing the closest match yet to Satoshi's, but the case collapsed against an alibi: at the times Satoshi was sending timestamped emails and confirming a block in April 2009, Finney, an avid runner, was competing in and photographed at a ten-mile road race in Santa Barbara. Greenberg concluded Finney was not Nakamoto, and Finney denied it.[^15][^16]

### Cryonics and Death

Finney was a member of the extropian and cryonics communities and had been an Alcor client for twenty years by the time he disclosed his ALS in the October 2009 LessWrong essay "Dying Outside." He was diagnosed in August 2009 and continued programming with a commercial eyetracker and speech synthesizer as the disease left him almost fully paralyzed, writing in 2013 that he could still code, "probably 50 times slower than I was before," and that he "still love[d] programming."[^11][^12]

Finney died on 28 August 2014 at age fifty-eight in [[Scottsdale]], [[Arizona]], and was cryopreserved by the Alcor Life Extension Foundation, later run by [[Max More]], as its 128th patient on the day of his death. Alcor's case summary records that he chose whole-body preservation, funded by life insurance and bitcoin donated by admirers. In December 2014 an extortionist who had demanded 1,000 bitcoin from the family, worth roughly 400,000 dollars, retaliated for non-payment by placing a false emergency call that sent an armed police team to the Finney home, an attack known as swatting.[^13][^14]

### Footnotes

[^1]: "Remembering Hal Finney: A Decade Since His Passing," *Nasdaq,* on his PGP work, the first Bitcoin transaction, RPOW, and his ALS. https://www.nasdaq.com/articles/remembering-hal-finney-decade-his-passing-his-legacy-bitcoin-lives
[^2]: "How cryonics and cryptography are related: from Hal Finney to CryoGen," *KrioRus,* on Finney's extropian and cryonics involvement and his Alcor preservation.
[^3]: "The Extropian Roots of Bitcoin," *CCN,* on Finney introducing digital cash to the extropians and building RPOW. https://www.ccn.com/extropian-roots-bitcoin/
[^4]: Finney, Hal. "RPOW: Reusable Proofs of Work," 2004, on the reusable proof-of-work design.
[^5]: Finney, Hal. "Bitcoin and me," Bitcointalk, 19 March 2013. https://bitcointalk.org/index.php?topic=155054.0
[^6]: "Hal Finney on Bitcoin: In His Own Words," *CoinDesk,* 29 August 2014, on the first transaction and the Satoshi speculation. https://www.coindesk.com/markets/2014/08/29/hal-finney-on-bitcoin-in-his-own-words
[^7]: "Meet the Cryonics Company Preserving Bitcoin Legend Hal Finney's Body," *Decrypt,* on his Alcor cryopreservation. https://decrypt.co/243997/cryonics-alcor-hal-finney-bitcoin
[^8]: "Hal Finney, cryptographer and bitcoin pioneer, dies," *The Boston Globe,* August 31, 2014, on his Caltech degree, APh and Mattel games, and his 1991 PGP work and hiring by Zimmermann. https://www.bostonglobe.com/metro/obituaries/2014/08/31/hal-finney-cryptographer-and-bitcoin-pioneer-dies/7aFf8qJ1ixkF98m7QU76RP/story.html
[^9]: Finney, Hal. "RPOW - Reusable Proofs of Work," cryptography mailing list, August 15, 2004. https://www.metzdowd.com/pipermail/cryptography/2004-August/007362.html
[^10]: Finney, Hal. "RPOW - IBM 4758 Security Model," on the FIPS 140 Level 4 coprocessor, the device key, and the real-time attestation of the running software. https://nakamotoinstitute.org/finney/rpow/secmodel.html
[^11]: Finney, Hal. "Dying Outside," LessWrong, October 5, 2009, on the ALS diagnosis and his Alcor membership. https://www.lesswrong.com/posts/bshZiaLefDejvPKuS/dying-outside
[^12]: Finney, Hal. "Bitcoin and me," Bitcointalk, March 19, 2013, on the eyetracker, his slowed coding, and moving coins to an offline wallet. https://bitcointalk.org/index.php?topic=155054.0
[^13]: "Case Summary A-1436," Alcor Life Extension Foundation, on the August 28, 2014 death in Scottsdale, the whole-body option, and his status as Alcor's 128th patient. https://www.cryonicsarchive.org/library/complete-list-of-alcor-cryopreservations/case-summary-a-1436/
[^14]: "Bitcoin Extortionist Targeted Hal Finney and Others," *NewsBTC,* December 30, 2014, on the 1,000-bitcoin demand and the swatting of the Finney home. https://newsbtc.com/2014/12/30/bitcoin-extortionist-targeted-hal-finney-others
[^15]: Goodman, Leah McGrath. "The Face Behind Bitcoin," *Newsweek,* March 6, 2014, naming Dorian Prentice Satoshi Nakamoto of Temple City. https://www.newsweek.com/2014/03/14/face-behind-bitcoin-247957.html
[^16]: Greenberg, Andy. "Nakamoto's Neighbor: My Hunt For Bitcoin's Creator Led To A Paralyzed Crypto Genius," *Forbes,* March 25, 2014, on the Juola stylometric analysis and the road-race alibi clearing Finney. https://www.forbes.com/sites/andygreenberg/2014/03/25/satoshi-nakamotos-neighbor-the-bitcoin-ghostwriter-who-wasnt/

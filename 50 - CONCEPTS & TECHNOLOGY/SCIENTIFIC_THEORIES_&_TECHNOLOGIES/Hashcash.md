---
category: "Scientific Theory & Technology"
tags:
  - Concept
  - Hashcash
  - ProofOfWork
  - Cryptography
  - Cypherpunks
  - Bitcoin
  - AdamBack
alias:
  - Hashcash
  - hashcash
summary: "Hashcash is the 1997 proof-of-work scheme that Adam Back devised to price email and deter spam by forcing a sender to compute a partial hash collision, and which the 2008 Bitcoin white paper cited as the model for the proof-of-work that secures the network and issues new coins."
location: "United States"
created: 2026-06-20
updated: 2026-06-20
---

Hashcash is a proof-of-work scheme that the British cryptographer [[Adam Back]] proposed in 1997 to deter email spam and denial-of-service attacks by attaching a small computational cost to each message. A sender must find an input whose cryptographic hash begins with a required number of zero bits, a task that takes a predictable amount of processor work to complete but that a recipient can verify in an instant. [[Satoshi Nakamoto]] cited Hashcash in the 2008 [[Bitcoin]] white paper as the basis for the proof-of-work that orders the blockchain and governs the creation of new coins.[^1][^2]

### The Spam Problem and the Mechanism

Back announced Hashcash on March 28, 1997, in a message to the roughly two thousand subscribers of the [[Cypherpunks|cypherpunks]] mailing list, describing it as a "partial hash collision based postage scheme," a stamp for email whose cost fell on the sender. The aim was to make the marginal cost of sending a message high enough to ruin the economics of mass spam, where a spammer sends millions of messages, while leaving an ordinary correspondent who sends a few messages effectively unburdened. The same mechanism could throttle abusive connections to a server and so blunt denial-of-service attacks.[^2][^3]

The scheme works by partial hash inversion. The sender assembles a token containing the recipient address, a date, and a random counter, then repeatedly increments the counter and hashes the token, originally with the SHA-1 function, until the resulting digest begins with a set number of leading zero bits; Back's design proposed twenty. Because a good hash function is unpredictable, the only way to find such an input is to try enormous numbers of counters, so producing a valid token costs on average about a million hash computations for twenty zero bits, while a recipient confirms it with a single hash. Back captured the asymmetry in his announcement: "The idea of using partial hashes is that they can be made arbitrarily expensive to compute, and yet can be verified instantly." Raising the number of required zero bits raises the sender's cost exponentially while leaving verification trivial.[^2][^4]

### Origins and the 2002 Paper

Hashcash drew on an idea the cryptographers Cynthia Dwork and Moni Naor had set out in their 1992 paper "Pricing via Processing or Combatting Junk Mail," which proposed charging a sender a moderately hard computation as the price of sending a message, a cost the authors called a pricing function. Back arrived at his partial-hash construction independently and turned the idea into a concrete, deployable email stamp. He circulated the design on the cypherpunks list and later set it out formally in the 2002 paper "Hashcash - A Denial of Service Counter-Measure," which described the cost function, the choice of hash, and the double-spending and minting questions that any such token scheme raises.[^3][^5]

As an anti-spam measure Hashcash saw only limited deployment, and it was added as an optional header in a few mail systems without becoming standard. Its lasting importance came from the proof-of-work primitive at its center, the property that a token is expensive to make and cheap to check. [[Hal Finney]] built directly on Hashcash in 2004 with reusable proof-of-work, which accepted a Hashcash token and returned a signed token that could be passed from person to person, and [[Wei Dai]]'s b-money proposal envisioned participants creating money by solving computational problems, two of the lines of work that converged on cryptocurrency.[^3][^6]

### The Bitcoin Citation

The 2008 Bitcoin white paper cites Hashcash directly. In the section on proof-of-work it states, "To implement a distributed timestamp server on a peer-to-peer basis, we will need to use a proof-of-work system similar to Adam Back's Hashcash," and the reference list includes Back's 2002 paper. Bitcoin keeps the partial-hash mechanism almost unchanged in form, requiring that the hash of a block header fall below a target value, which is equivalent to demanding a set number of leading zero bits, but it applies the mechanism to a different problem. Where Hashcash priced a single email, Bitcoin uses the work to decide which version of a public ledger the network accepts.[^7][^1]

In Bitcoin the miner who first finds a valid block is rewarded with newly created coins, so the proof-of-work both secures the transaction history and meters the issuance of the currency, and the white paper summarizes the consensus rule as "proof-of-work is essentially one-CPU-one-vote." Back has recounted that Nakamoto emailed him in August 2008 asking how Hashcash should be cited, the earliest message from Nakamoto known to be addressed to a named individual. The double hash Bitcoin computes uses SHA-256 rather than the SHA-1 of Back's original, and the network periodically adjusts the required difficulty so that blocks arrive at a roughly constant rate as total mining power changes.[^7][^8]

### Footnotes

[^1]: Nakamoto, Satoshi. "Bitcoin: A Peer-to-Peer Electronic Cash System," 2008, citing Adam Back's Hashcash and stating "proof-of-work is essentially one-CPU-one-vote." https://bitcoin.org/bitcoin.pdf
[^2]: "The Genesis Files: Hashcash or How Adam Back Designed Bitcoin's Motor Block," *Bitcoin Magazine,* on the March 28, 1997 announcement, the "partial hash collision based postage scheme" phrasing, the SHA-1 twenty-zero-bit design, and the "arbitrarily expensive to compute, and yet can be verified instantly" quote. https://bitcoinmagazine.com/technical/genesis-files-hashcash-or-how-adam-back-designed-bitcoins-motor-block
[^3]: Back, Adam. "Hashcash - A Denial of Service Counter-Measure," 2002, on the partial-hash-collision cost function, the spam and denial-of-service application, and the relation to Dwork and Naor. http://www.hashcash.org/papers/hashcash.pdf
[^4]: "Hashcash: Proof of Work applied to emails," *Atlas21,* on the leading-zero-bit mechanism and verification asymmetry. https://atlas21.com/hashcash-proof-of-work-applied-to-emails/
[^5]: Dwork, Cynthia, and Moni Naor. "Pricing via Processing or Combatting Junk Mail," *Advances in Cryptology: CRYPTO '92,* 1992, on the pricing-function idea that preceded Hashcash. https://www.wisdom.weizmann.ac.il/~naor/PAPERS/pvp.pdf
[^6]: "The Extropian Roots of Bitcoin," *CCN,* on Finney's reusable proof-of-work built from Hashcash and Wei Dai's b-money. https://www.ccn.com/extropian-roots-bitcoin/
[^7]: "Bitcoin: A Peer-to-Peer Electronic Cash System," Satoshi Nakamoto Institute, on the line "we will need to use a proof-of-work system similar to Adam Back's Hashcash" and the proof-of-work and coin-issuance sections. https://nakamotoinstitute.org/library/bitcoin/
[^8]: "Who is Adam Back? The impact of Hashcash on Bitcoin explained," *Finst,* on Nakamoto's August 2008 email to Back asking how to cite Hashcash. https://finst.com/en/learn/articles/who-is-adam-back

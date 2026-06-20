---
category: "Scientific Theory & Technology"
tags:
  - Concept
  - BlackNet
  - Cypherpunks
  - CryptoAnarchy
  - DigitalCash
  - Anonymity
  - TimothyMay
alias:
  - BlackNet
summary: "BlackNet was Timothy May's 1993 thought experiment for an anonymous information market built on public-key encryption, remailers, message pools, and digital cash, circulated on the cypherpunks list as a working precursor to dark markets and anonymous-leak platforms."
location: "United States"
created: 2026-06-20
updated: 2026-06-20
---

BlackNet was an anonymous information market that the former [[Intel]] scientist [[Timothy May]] described and circulated in 1993 as a proof of concept for the [[Cypherpunks]] movement, using public-key encryption, chains of anonymous remailers, publicly readable message pools, and untraceable digital cash to let parties buy and sell information without ever learning one another's identities. May seeded it on the cypherpunks mailing list and through remailers, later acknowledging that he had written it to demonstrate that crypto-anarchist information markets were already technically possible.[^1][^2]

### The BlackNet Message

The BlackNet announcement opened "Your name has come to our attention. We have reason to believe you may be interested in the products and services our new organization, BlackNet, has to offer. BlackNet is in the business of buying, selling, trading, and otherwise dealing with *information* in all its many forms." It solicited "trade secrets, processes, production methods," along with "nanotechnology and related techniques," chemical-manufacturing methods, product and business plans, and other restricted material, and it offered to sell the same. It told correspondents to reach it by posting [[Pretty Good Privacy|PGP]]-encrypted messages through an anonymous remailer chain to public forums such as Usenet groups and mailing lists, where the operators could read them without any return path existing.[^3]

The message framed its security in cryptographic terms, promising "public key cryptosystems with essentially perfect security" and assuring respondents that "unless you tell us who you are (please don't!) or inadvertently reveal information which provides clues, we have no way of identifying you." For payment it accepted "anonymous deposits to the bank account of your choice," cash sent by mail, or "CryptoCredits," a closed-loop internal currency for use within the market. The design used a message pool, a widely broadcast public space where anyone could deposit and read messages anonymously, so that neither buyer nor seller had to connect to the other directly and the market itself had no fixed address to seize.[^3][^1]

### Crypto-Anarchy and Distribution

BlackNet was an application of the crypto-anarchist program May had set out in "The Crypto Anarchist Manifesto" of 1988 and developed in his 1994 reference document the Cyphernomicon. It combined the cypherpunk toolkit already in use on the list, PGP encryption, the remailer chains descended from the work of [[John Gilmore]] and [[Eric Hughes]], and the anonymous digital cash modeled on [[David Chaum]]'s blind-signature schemes, into a single illustration of an untraceable market for forbidden information. May posted the design anonymously and let it propagate through remailers, and in his essay "Crypto Anarchy and Virtual Communities" he described BlackNet as "a system which appeared in 1993 and which allows fully-anonymous, two-way exchanges of information of all sorts."[^4][^2]

The text spread widely and reached United States government research sites; May recorded that the message turned up at Defense Department national laboratories and drew official attention, after which he acknowledged authorship and explained that he had built it as a teaching example rather than a live operation. He treated the exercise as proof that the components already existed, so that the question was not whether such markets could be built but what would follow once they were. The market relied on no central server or operator who could be compelled to identify users.[^2][^1]

### Precursor to Dark Markets and Leak Platforms

BlackNet anticipated the structure of the anonymous information markets and leak platforms that emerged in the following two decades. Its message pool and remailer architecture prefigured the anonymous submission systems of [[WikiLeaks]], which built its early intake on encryption and remailer-style anonymity drawn from the same cypherpunk practice, and its combination of an anonymous market with untraceable digital cash prefigured the cryptocurrency dark markets such as the Silk Road that followed [[Bitcoin]]. The digital-cash element of BlackNet pointed at the gap that Chaum's centralized [[eCash]] could not fill and that the later proof-of-work currencies, [[Adam Back]]'s [[Hashcash]], [[Nick Szabo]]'s [[bit gold]], [[Wei Dai]]'s [[b-money]], and finally Bitcoin, were built to close.[^1][^5]

May's premise, that strong encryption and anonymous payment would let information and money escape state control, was the same premise the cypherpunk digital-cash thread carried into Bitcoin and that WikiLeaks tested against the banking system in 2010. BlackNet itself never operated as a real market; it stood as a demonstration that the tools were in hand.[^2][^5]

### Footnotes

[^1]: "Dark Markets: Tim May's BlackNet," *ChainRift Research,* on the 1993 design, the remailers, PGP, the message pool, CryptoCredits, and the items solicited. https://medium.com/chainrift-research/dark-markets-tim-mays-blacknet-7b7738e0617c
[^2]: May, Timothy C. "Crypto Anarchy and Virtual Communities," 1994, describing BlackNet as a 1993 system for fully anonymous two-way exchanges of information and noting its appearance at Defense Department labs. https://groups.csail.mit.edu/mac/classes/6.805/articles/crypto/cypherpunks/may-virtual-comm.html
[^3]: May, Timothy C. "BlackNet" message, 1993, on the opening text, the public-key-cryptosystem promise, the CryptoCredits payment, the anonymous bank deposits, and the remailer-and-Usenet contact method. https://groups.csail.mit.edu/mac/classes/6.805/articles/crypto/cypherpunks/blacknet.txt
[^4]: May, Timothy C. *The Cyphernomicon,* 1994, on BlackNet within the crypto-anarchist program and the cypherpunk toolkit. https://nakamotoinstitute.org/static/docs/cyphernomicon.txt
[^5]: "The Extropian Roots of Bitcoin," *CCN,* on the digital-cash precursors of bit gold, RPOW, and b-money. https://www.ccn.com/extropian-roots-bitcoin/

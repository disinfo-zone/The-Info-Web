---
category: "Scientific Theory & Technology"
tags:
  - Concept
  - PGP
  - Cryptography
  - Cypherpunks
  - Privacy
  - CryptoWars
  - PhilZimmermann
alias:
  - PGP
  - Pretty Good Privacy
summary: "Pretty Good Privacy is the email-encryption software Phil Zimmermann released for free in 1991, whose international spread triggered a three-year US criminal investigation that treated strong cryptography as a munition and that the cypherpunks made a central front of the crypto wars."
location: "United States"
created: 2026-06-20
updated: 2026-06-20
---

Pretty Good Privacy (PGP) is an email-encryption program written by [[Phil Zimmermann]] and released for free in June 1991, which combined public-key cryptography with symmetric encryption to let ordinary users sign and encrypt messages and files. Its release and rapid spread beyond the United States provoked a three-year federal criminal investigation that treated the software as an illegally exported munition, and PGP became a central artifact of the [[Cypherpunks]] movement and the [[Crypto Wars|crypto wars]] over the right to use strong encryption.[^1][^2]

### Release and Design

Zimmermann wrote in his own account that he was prompted by Senate Bill 266 of 1991, an anti-crime measure containing a non-binding sense-of-Congress provision that would have required manufacturers of secure communications equipment to build in "trap doors" so the government could read encrypted traffic. He published PGP electronically for free that year, shortly before the bill's measure was dropped, framing the software as a way to "hold the line on privacy in the information age" and arguing that "the only way to hold the line on privacy in the information age is strong cryptography." He summarized the stakes in the slogan "If privacy is outlawed, only outlaws will have privacy."[^3]

PGP used a hybrid scheme: it generated a random session key to encrypt the message body with a fast symmetric cipher, then encrypted that session key with the recipient's RSA public key, so anyone could send an encrypted message to a published key while only the holder of the private key could read it. It also supported digital signatures, letting a sender prove authorship and a recipient detect tampering, and it relied on a decentralized "web of trust" in which users signed one another's keys rather than depending on a central certificate authority. Because PGP incorporated the RSA algorithm, which was patented in the United States, its early distribution also drew complaints from RSA Data Security over patent use.[^1][^4]

### The Criminal Investigation

Within hours of its release, PGP spread over the internet and reached users outside the United States, which placed it under the International Traffic in Arms Regulations (ITAR), the export-control regime that classified strong cryptographic software as a munition requiring a license to export. In February 1993 federal investigators visited Zimmermann, and after questions about RSA patent infringement they turned to the more serious charge of exporting a weapon without a license. The United States Customs Service opened a criminal investigation in 1993, run out of the office of the United States Attorney for the Northern District of California, into whether Zimmermann had violated the export rules when PGP traveled abroad.[^1][^2]

Zimmermann and his supporters answered with a First Amendment argument that source code is protected speech. In 1995 the MIT Press published "PGP: Source Code and Internals," a roughly 900-page book containing the complete formatted source code of PGP 2.6.2, printed in a font designed for optical character recognition so that the code could be exported legally as a printed book, scanned abroad, and recompiled. The tactic tested whether the government would treat the printed word as a munition. The investigation closed without charges in January 1996, when United States Attorney Michael J. Yamaguchi for the Northern District of California announced that his office had declined to prosecute anyone in connection with the 1991 USENET posting of PGP.[^5][^6]

### The Crypto Wars and the Cypherpunk Distribution

The PGP investigation ran in parallel with the broader crypto wars of the 1990s, in which the cypherpunks fought the ITAR munitions classification and the Clinton administration's 1993 "Clipper chip" proposal for key-escrow encryption that would have given the government a copy of every key. PGP circulated through the cypherpunk network of anonymous remailers and mirror sites and became the standard tool for the movement's encrypted communications; [[Hal Finney]] was a central contributor to PGP 2.0 from 1991 and was hired by Zimmermann when the investigation closed, and [[Timothy May]]'s [[BlackNet]] thought experiment was built around PGP public keys and remailers.[^7][^8]

The export-control regime collapsed at the end of the decade. The federal court in Bernstein v. United States ruled in 1996 that source code is speech protected by the First Amendment and that the export licensing scheme was an unconstitutional prior restraint, the Clipper proposal failed after the cryptographer Matt Blaze exposed a flaw in its escrow protocol in 1994, and in late 1999 the Clinton administration announced a broad relaxation of crypto export controls. Zimmermann later wrote that "we have finally won, at least on the export control front in the US." PGP itself passed through a series of corporate owners and was reimplemented in the open OpenPGP standard and the free GNU Privacy Guard, which carried the design forward.[^9][^3]

### Footnotes

[^1]: "Phil Zimmermann: PGP, the Crypto Wars, and the Right to Encrypted Communication," *Immunity Networks,* on the 1991 release, the hybrid design, the ITAR investigation, and the resolution. https://blog.immunitynetworks.com/phil-zimmermann-pgp-encryption-privacy-crypto-wars/
[^2]: Levy, Steven. *Crypto: How the Code Rebels Beat the Government, Saving Privacy in the Digital Age.* Viking, 2001.
[^3]: Zimmermann, Philip. "Why I Wrote PGP," on Senate Bill 266, the free electronic release, the "only outlaws will have privacy" line, and the 1999 export-policy reversal. https://www.philzimmermann.com/EN/essays/WhyIWrotePGP.html
[^4]: "Cypherpunks Write Code," *American Scientist,* on PGP, the RSA patent friction, and the crypto wars. https://www.americanscientist.org/article/cypherpunks-write-code
[^5]: Zimmermann, Philip R. *PGP: Source Code and Internals.* MIT Press, 1995, the printed source code of PGP 2.6.2. https://archive.org/details/pgpsourcecodeint0000zimm
[^6]: "Case Closed on Zimmermann PGP Investigation," *IEEE Cipher,* February 1996, on US Attorney Yamaguchi declining prosecution over the June 1991 USENET posting. https://www.ieee-security.org/Cipher/Newsbriefs/1996/960214.zimmerman.html
[^7]: "Hal Finney, cryptographer and bitcoin pioneer, dies," *The Boston Globe,* 31 August 2014, on Finney's PGP 2.0 contributions and his hiring by Zimmermann when the investigation closed. https://www.bostonglobe.com/metro/obituaries/2014/08/31/hal-finney-cryptographer-and-bitcoin-pioneer-dies/7aFf8qJ1ixkF98m7QU76RP/story.html
[^8]: May, Timothy C. *The Cyphernomicon,* 1994, on PGP, remailers, and BlackNet in the cypherpunk toolkit. https://nakamotoinstitute.org/static/docs/cyphernomicon.txt
[^9]: "Bernstein v. U.S. Dept. of Justice," Electronic Frontier Foundation, on the 1996 ruling that source code is protected speech and the licensing scheme an unconstitutional prior restraint. https://www.eff.org/cases/bernstein-v-us-dept-justice

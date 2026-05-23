---
category: "Organizations"
tags:
  - Organization
  - TheCom
  - CyberCom
  - Cybercrime
  - SIMSwapping
  - Ransomware
  - Phishing
  - CryptocurrencyTheft
  - FederalCase
  - USA
  - UK
created: 2026-05-21
updated: 2026-05-21
summary: "Scattered Spider is a Cyber Com cybercriminal group of English-speaking teenagers and young adults known for SMS phishing, SIM swapping, and ransomware against major corporations, with at least eight members charged or convicted as of mid-2026."
start: 2021
location: "Online (USA/UK primarily)"
---

[[Scattered Spider]] is a loosely organized cybercriminal group operating within the Cyber Com sphere of [[The Com]] ecosystem. It is composed predominantly of English-speaking teenagers and young adults based in the [[United States]] and the [[United Kingdom]], who coalesced through online gaming communities and criminal forums. Scattered Spider became the highest-profile Cyber Com group through a series of attacks on major corporations between 2022 and 2025, culminating in the 2023 ransomware attacks on [[MGM Resorts]] and [[Caesars Entertainment]]. The group is also tracked under the aliases 0ktapus, Roasted 0ktapus, UNC3944, Octo Tempest, Storm-0875, and Starfraud, with different aliases assigned by different cybersecurity research firms. As of mid-2026, at least eight individuals had been charged in the United States or United Kingdom in connection with Scattered Spider operations.[^1]

### The Com Connection

[[SANS Institute]] and [[CyberScoop]] both document Scattered Spider as a product of The Com's Cyber Com sphere, describing the group as having "evolved out of The Com" with "a common set of intrusion techniques observed across multiple high-profile breaches." The Com's Cyber Com sphere uses SIM swapping, IP grabbing, doxxing, and swatting as shared tradecraft across groups; Scattered Spider adopted and industrialized these methods at scale. The broader Com ecosystem includes participants in the Sextortion Com sphere (dominated by [[764 Network|764]]) and the Offline Com sphere; Scattered Spider's operations are confined to the Cyber Com sphere, though its members overlap socially with the broader community. Law enforcement intelligence documents obtained by CyberScoop confirm the FBI investigates the Com as a unified threat rather than as separate phenomena.[^2]

### History and Operations

Scattered Spider is believed to have first coalesced around May 2021-2022, initially focusing on attacks against telecommunications companies and business process outsourcing (BPO) firms to enable SIM swapping. The group ran a [[Telegram]] channel from approximately 2022 that served as a hub for SIM-swapping operations targeting major wireless carriers in the U.S. and UK.

#### 2022: The 0ktapus Campaign

In summer 2022, Scattered Spider executed a mass SMS phishing campaign against more than 130 organizations, building convincing spoofed [[Okta]] login pages to harvest credentials and session tokens at scale. Documented victims included [[Twilio]], [[Cloudflare]], [[DoorDash]], [[Mailchimp]], and [[LastPass]]. The campaign was named "0ktapus" by security researchers after the fake Okta infrastructure used. The November 2024 federal indictment covers the period September 2021 through April 2023 and charges the five defendants with attacking at least 45 companies and stealing at least $11 million in cryptocurrency from at least 29 victims.

#### 2023: MGM and Caesars

In September 2023, Scattered Spider executed its most consequential operations. For the [[Caesars Entertainment]] attack, the group used social engineering to gain access, obtained sensitive data, and extorted Caesars for a $15 million ransom payment (half the original demand of $30 million). For the [[MGM Resorts International]] attack, attackers used voice phishing (vishing) to impersonate an IT helpdesk employee, conducted SIM swapping, obtained MFA reset codes, gained network access, and deployed [[ALPHV]]/BlackCat ransomware across MGM's ESXi servers. The MGM attack caused approximately one week of operational disruption and an estimated $100 million in lost revenue and recovery costs.

#### 2025: UK Retail Attacks

Scattered Spider or affiliated actors attacked three major UK retailers in 2025: [[Marks and Spencer]], [[Harrods]], and [[Co-op]]. The Marks and Spencer attack caused significant operational disruption. The UK [[National Crime Agency]] (NCA) and [[City of London Police]] arrested four individuals in connection with these attacks in July 2025.

#### 2025: Healthcare and Infrastructure

The September 2025 DOJ indictment against [[Thalha Jubair]] alleged participation in at least 120 cyberattacks between May 2022 and September 2025, including against [[SSM Health Care Corporation]] and attempted attacks against [[Sutter Health]], with aggregate ransom payments from victims of at least $115 million.[^3]

### Tactics

Scattered Spider's documented methods include:

- SMS phishing ("smishing"): mass text campaigns mimicking IT help desks and single sign-on portals
- Voice phishing ("vishing"): impersonating employees or IT staff in calls to corporate help desks
- SIM swapping: bribing or deceiving telecom employees to transfer a victim's phone number, enabling MFA bypass
- MFA push bombing: repeatedly sending authentication requests to exhaust and confuse a target
- Social engineering of IT help desks to issue MFA resets to attacker-controlled devices
- Ransomware deployment (via ALPHV/BlackCat partnership) after network access achieved
- Cryptocurrency theft via compromised exchange accounts
- Data exfiltration and extortion independent of ransomware

### Members and Legal Proceedings

#### November 20, 2024 Indictment (Central District of California)

The U.S. Attorney's Office for the Central District of California unsealed charges against five defendants on November 20, 2024, covering the period September 2021 through April 2023. All five were charged with conspiracy to commit wire fraud, conspiracy, and aggravated identity theft (maximum 20 years per conspiracy count; mandatory 2-year consecutive term for aggravated identity theft):

- [[Ahmed Hossam Eldin Elbadawy]], 23, of College Station, Texas (alias "AD"): still facing charges as of mid-2026
- [[Evans Onyeaka Osiebo]], 21, of Dallas, Texas: still facing charges as of mid-2026
- [[Noah Michael Urban]], 20, of Palm Coast, Florida (aliases "King Bob," "Gustavo Fring"): pleaded guilty; sentenced
- [[Joel Martin Evans]], 26, of Jacksonville, North Carolina (alias "joeleoli"): still facing charges as of mid-2026
- [[Tyler Robert Buchanan]], 22, of the United Kingdom (alias "tylerb"): pleaded guilty; sentencing pending

[[Noah Michael Urban]] pleaded guilty in April 2025 in the Middle District of Florida (Jacksonville) and Central District of California. He was sentenced on August 20, 2025, by U.S. District Judge [[Harvey Schlesinger]] in Jacksonville, Florida, to 120 months (10 years) in federal prison, three years of supervised release, and $13,049,490.64 in restitution to 59 victim individuals. Urban was the first Scattered Spider member to be sentenced. Prosecutors had requested eight years; Urban's defense requested five years; Judge Schlesinger exceeded both recommendations.

[[Tyler Robert Buchanan]] was arrested by Spanish authorities in June 2024 while attempting to board a flight to Italy. He was extradited to the United States and entered federal custody in April 2025. Buchanan pleaded guilty to wire fraud conspiracy and aggravated identity theft, admitting his role in the 2022 SMS phishing campaign against major technology companies. He received an additional wire fraud count compared to the other four November 2024 defendants, giving him a potential maximum term of approximately 22 years. Sentencing is scheduled for August 21, 2026.

[[Remington Goy Ogletree]], 19, of Texas and Florida, was charged on October 30, 2024 with wire fraud in connection with conduct between October 2023 and May 2024. He was arrested in California shortly after charges were filed. Ogletree is alleged to have phished nearly 150 employees of a U.S. financial institution, gained unauthorized access to telecommunications company networks, and used that access to deliver more than 8.6 million SMS phishing messages targeting [[Gemini]] and [[KuCoin]] cryptocurrency exchange users, enabling theft of over $4 million in cryptocurrency. He is at least the sixth Scattered Spider member to face federal charges.

[[Thalha Jubair]], 19, of East London, was arrested at his home on September 16, 2025, by the NCA and City of London Police. The District of New Jersey unsealed charges against Jubair on September 18, 2025: conspiracy to commit computer fraud, wire fraud conspiracy, money laundering conspiracy, and substantive computer fraud counts. Jubair is alleged under the alias "EarthtoStar" (also "Brad," "Austin," "@autistic," and "Operator") to have participated in at least 120 network intrusions affecting at least 47 U.S. organizations between May 2022 and September 2025, generating at least $115 million in ransom payments to the group. He also faces UK charges under the Computer Misuse Act for the Transport for London (TfL) attack and under the Regulation of Investigatory Powers Act for refusing to disclose device passwords. He and co-defendant Owen Flowers denied the TfL charges at Southwark Crown Court. If convicted on all U.S. counts, Jubair faces a maximum of 95 years in prison.

[[Owen David Flowers]], 18, of Walsall, West Midlands, was arrested alongside Jubair on September 16, 2025. Flowers used the hacker handles "bo764," "Holy," and "Nazi" and was alleged to have participated in the September 2023 MGM attack; he gave anonymous media interviews about the MGM hack in the days following the attack. Flowers and Jubair denied the Computer Misuse Act charges at Southwark Crown Court.

#### July 2025 UK Arrests

The NCA arrested four individuals in July 2025 in connection with the 2025 UK retail attacks (Marks and Spencer, Harrods, Co-op). Of the four arrested, a 20-year-old woman, two 19-year-old men, and a 17-year-old were charged with computer misuse, extortion, money laundering, and membership in a criminal organization. The names of the July 2025 arrestees other than Thalha Jubair and Owen Flowers (arrested in September) were not publicly released in available reporting as of mid-2026.[^4]

### Footnotes

[^1]: CISA/FBI. "Cybersecurity Advisory AA23-320A: Scattered Spider." November 2023. https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-320a; Krebs on Security. "UK Arrests Four in 'Scattered Spider' Ransom Group." July 2025. https://krebsonsecurity.com/2025/07/uk-charges-four-in-scattered-spider-ransom-group/
[^2]: SANS Institute. "Defending Against SCATTERED SPIDER and The Com with Cybercrime Intelligence." https://www.sans.org/blog/defending-against-scattered-spider-and-the-com-with-cybercrime-intelligence/; CyberScoop. "Scottish man pleads guilty to attack spree that created Scattered Spider's notoriety." April 2026. https://cyberscoop.com/the-com-scattered-spider-hacker-tyler-robert-buchanan-guilty-plea/
[^3]: Krebs on Security. "Feds Tie 'Scattered Spider' Duo to $115M in Ransoms." September 2025. https://krebsonsecurity.com/2025/09/feds-tie-scattered-spider-duo-to-115m-in-ransoms/; Fortune. "London teenager orchestrated 'help desk' extortion scheme against 47 U.S. companies." September 20, 2025. https://fortune.com/2025/09/20/teenager-scattered-spider-extortion-ransom-arrested/
[^4]: Krebs on Security. "'Scattered Spider' Member 'Tylerb' Pleads Guilty." April 2026. https://krebsonsecurity.com/2026/04/scattered-spider-member-tylerb-pleads-guilty/; DataBreaches.Net. "Noah Urban aka 'King Bob' of Scattered Spider, sentenced to 10 years in prison, $13 million restitution." August 21, 2025. https://databreaches.net/2025/08/21/noah-urban-aka-king-bob-of-scattered-spider-sentenced-to-10-years-in-prison-13-million-restitution/; SecurityWeek. "Suspected Scattered Spider Hacker Pleads Guilty." https://www.securityweek.com/suspected-scattered-spider-hacker-pleads-guilty/; The Hacker News. "U.K. Arrests Two Teen Scattered Spider Hackers Linked to August 2024 TfL Cyber Attack." September 2025. https://thehackernews.com/2025/09/uk-arrest-two-teen-scattered-spider.html

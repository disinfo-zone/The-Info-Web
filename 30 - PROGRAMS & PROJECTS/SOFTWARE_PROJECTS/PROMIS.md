---
title: PROMIS
aliases:
  - PROMIS
  - Prosecutor's Management Information System
created: 2024-04-25
updated: 2026-05-17
tags:
  - PROMIS
  - INSLAW
  - Conspiracy
  - Software
  - Intelligence
  - CIA
  - DOJ
category: "Software Project"
summary: "PROMIS (Prosecutor's Management Information System) was a case management software developed by INSLAW beginning in 1971 that became the center of a major legal and intelligence scandal after the U.S. Justice Department allegedly stole the proprietary version and distributed it internationally with a hidden surveillance backdoor."
start: 1971-01-01
location: "Washington, D.C."
---
PROMIS (Prosecutor's Management Information System) was a pioneering case management software system developed in the 1970s and 80s by [[INSLAW|The Institute for Law and Social Research]] (INSLAW). The software was originally designed to help the [[U.S. Attorney's office]] in DC automate and streamline their case management processes. This expanded across the country and internationally. However, it later became embroiled in controversy, theft, and conspiracy theories.
### Origins and Development

In 1969, US Attorney [[Thomas A. Flannery]] perceived an urgent need for new techniques for dealing with the overwhelming amount of cases going through the DC U.S. Attorney's Office. The [[Office of Crime Analysis of the District of Columbia]] (funded by the [[LEAA|Law Enforcement Assistance Administration]] (LEAA)) gave a $60,000 grant (70-DF-047) to [[Peat, Marwick, Mitchell & Co]] that put together a team of lawyers, management analysts, criminologists, statisticians, and computer science specialists to development a computer-based information system for the prosecutor.

This team was headed by [[Joan E. Jacoby]] (then Director of the Office of Crime Analysis of the District of Columbia) and [[Charles R. Work]] (then Deputy Chief of the Superior Court Division of the U.S. Attorney's office) with project manager [[Bill Hamilton]] (senior consultant at Peat, Marwick, Mitchell & Co, formerly [[NSA]] analyst). Other team members included [[Sidney H. Brounstein]], [[Robert H. Cain]], [[Joyce H. Deroy]], [[James M. Etheridge]], [[John L. Gizzarelli]], [[Fred L. Lander III]], [[Soo Lee]], [[Dean C. Merrill]], [[John M. Middleton]], [[Stanley H. Turner]], [[Frederick G. Watts]], [[Dennis W. Wright]], and [[Robert Whitaker]]. The design work occupied approximately 14 months.

The system came to be known as the Prosecutor's Management Information System (PROMIS) and deployed on January 1, 1971 in Washington D.C. for the District Attorney's Office. 

PROMIS had four basic subsystems: Report Generator, Forms Generator, Generalized Inquiry Package, Management Report Package. It could track case details, court schedules, witness information, and even “score” how important cases were (and later how likely someone was to commit another crime).

The software operated in batch processing mode (no online capabilities) and was designed to run on LEAA's [[IBM]] mainframe. It used a flat file database structure, and had no online data entry or inquiry capabilities. Original PROMIS was written in PL/I but was reprogrammed to COBOL for subsequent versions.

Around 1973 (date unclear), Bill Hamilton and [[Nancy Hamilton]] founded The Institute of Law and Social Research, a non profit think tank that was to be the steward of the PROMIS software. The LEAA declared PROMIS an "exemplary project" and further funded INSLAW to enhance PROMIS to make it a transferrable system that could be adopted by other jurisdictions. The LEAA also funded "transfers" for municipalities to adopt the PROMIS software.

This new version of the software was called PROMIS II.
### PROMIS II (mid-1970s)

In February 1973, US Attorney for DC [[Harold H. Titus Jr]] made the decision to upgrade PROMIS to a real-time on-line system capable of more than 160 variables per case.

- Enhanced version funded by LEAA to make the system transferable to other jurisdictions.
- Still primarily batch-oriented, but added online inquiry capabilities so users could look up case status and defendant information interactively.
- Implemented in New Orleans and Indianapolis.
- New Orleans ran PROMIS II on a DEC PDP-11/70 minicomputer dedicated to the prosecutor's office.
- Indianapolis operated PROMIS II on the city's IBM mainframe in a time-sharing mode.
### MINI-PROMIS (late 1970s)

- Minicomputer version of PROMIS designed to work with non-buffered character-oriented terminals.
- Could be implemented on a dedicated minicomputer or a time-shared mainframe.
- Rewritten in ANSI COBOL for easier portability between different computer systems.
- Featured a full-screen, menu-driven user interface for data entry and inquiry.
- Provided the "tailoring" capability to let each jurisdiction customize their database, screens, edits, and reports without programming.
- Produced outputs include case listings, defendant calendars, disposition reports, and more.
### MAXI-PROMIS / NEW-PROMIS (late 1970s)

- Minicomputer version that was a step up from MINI-PROMIS, utilizing newer "smart" buffered terminals.
- Also written in ANSI COBOL for portability and could run on minis or mainframes.
- Further improved the "tailoring" facility to make it easier for jurisdictions to adapt the system to their needs.
- Provided all the same online data entry, inquiry, and reporting features as MINI-PROMIS.
- Allowed integration with other criminal justice systems like police and corrections when implemented as a regional system, as in Colorado.
- Supported privacy segmentation for example Portland, Oregon implemented NEW-PROMIS on the county's mainframe, but partitioned it to be accessible only by the prosecutor's office.

Both MINI-PROMIS and MAXI-PROMIS continued to produce the traditional batch reports for management analysis, in addition to their online capabilities. The "tailoring" facility was a key feature that made these versions attractive for wider adoption, as jurisdictions could avoid much of the custom programming that was typically required to modify a transferred system to fit their local needs and terminology. However, implementing a PROMIS system still required some level of data processing expertise to set up the files, load the data, and customize the tables that drove the tailored features. INSLAW was usually hired to complete this process.
### PROMIS 82 / Enhanced PROMIS

"PROMIS 82" refers to the proprietary enhanced version of PROMIS that INSLAW claimed to have developed using private funds after May 1981, distinct from the public-domain versions developed under LEAA and BJS grants. The enhancements introduced a relational database structure, replaced the flat-file system of earlier versions, and added capabilities including the ability to integrate data across case types and generate probabilistic assessments of recidivism risk.

The critical legal distinction in the [[PROMIS Software Scandal]] turned on whether the 1982 DOJ implementation contract required delivery of only the public-domain version or also incorporated these privately-funded enhancements. INSLAW argued that the enhancements were inseparably integrated into the delivered system; DOJ argued the contract entitled it only to the public-domain base, and any proprietary enhancements had to be separately identified and could be removed.

The specific version delivered under Modification 12 on April 20, 1983, ran on a VAX minicomputer and is sometimes referred to as "VAX PROMIS." A Prime computer port was completed in August 1983 and installed across 20 U.S. Attorneys' offices. These VAX and Prime implementations were the versions at issue in the bankruptcy court litigation and in allegations that DOJ distributed enhanced PROMIS beyond the authorized 94 U.S. Attorneys' offices.[^1]
### Theft and Misappropriation by the U.S. Justice Department

In March 1982, INSLAW signed a $10 million, three-year contract with the [[Department of Justice|DOJ's]] Executive Office for United States Attorneys to install PROMIS in 20 large U.S. Attorneys' offices and word-processor systems in 74 smaller ones. From the outset, disputes arose over proprietary rights: INSLAW claimed the delivered software incorporated enhancements developed at private expense after May 1981, while DOJ insisted the contract entitled it to unlimited rights over everything delivered. Contract administrator [[Peter Videnieks]] and project manager [[C. Madison Brewer]] - the latter a former general counsel of INSLAW's predecessor organization - took consistently adversarial positions on INSLAW's proprietary claims.[^1]

DOJ withheld advance payments citing an unauthorized pledge of government invoices to a bank, a dispute INSLAW characterized as pretextual. Under financial duress, INSLAW filed for Chapter 11 bankruptcy protection in February 1985. The bankruptcy proceedings became a second front of litigation: INSLAW alleged that senior DOJ officials, including [[Lowell Jensen]] and acting under direction ultimately traceable to [[Edwin Meese]] and [[Earl Brian]], engineered the advance payment disputes specifically to drive the company into insolvency and enable the acquisition of its software at bankruptcy auction prices.

Bankruptcy Judge [[George Francis Bason, Jr.]] ruled in September 1987 that DOJ had "taken, converted, stole, INSLAW's enhanced PROMIS by trickery, fraud, and deceit." The D.C. Circuit Court affirmed this ruling in 1989. The Court of Appeals reversed it in 1991 on jurisdictional grounds; the Supreme Court declined review. Full legal history is documented at INSLAW and PROMIS Software Scandal.[^1][^2]

### Danny Casolaro and "The Octopus"

Freelance journalist [[Danny Casolaro]] began investigating the PROMIS Software Scandal in 1990 after being contacted by INSLAW founder Bill Hamilton.[^1] Casolaro believed the theft of PROMIS was one tentacle of a sprawling criminal conspiracy he called "[[The Octopus]]," which he believed linked U.S. intelligence agencies, international espionage and arms dealing, organized crime, drug cartels involved in the [[Iran-Contra Affair]], money laundering through [[Bank of Credit and Commerce International|BCCI]], and covert operations to manipulate foreign governments. He was working on a book titled "Behold, A Pale Horse" (later "The Octopus") encompassing these connected events.[^1]

Casolaro was found dead on August 10, 1991, in his hotel room in [[Martinsburg, West Virginia]], his wrists slashed twelve times. His death was ruled a suicide. His research files on PROMIS and the Octopus were missing from the hotel room. The House Judiciary Committee recommended further investigation into the circumstances of his death, and the case was later the subject of the 2024 documentary series *American Conspiracy: The Octopus Murders*. Full details are at Danny Casolaro.[^2][^8]

### The Backdoor Theory and International Proliferation

Multiple sources allege that U.S. and Israeli intelligence agencies modified PROMIS with a hidden surveillance backdoor before distributing it to foreign governments, banks, and international organizations. The backdoor allegedly allowed intelligence services to remotely access the databases of PROMIS users and monitor their queries in real time.

[[Michael Riconosciuto]] claimed he was tasked with installing the backdoor at the [[Wackenhut Corporation|Wackenhut]]-[[Cabazon Indian Reservation|Cabazon]] joint venture in Indio, California, working from software obtained through Earl Brian and Peter Videnieks. A separate account, drawn from Israeli intelligence sources and reported in Gordon Thomas's *Gideon's Spies* (1999), holds that [[Rafael Eitan]] of [[LAKAM]] directed Israeli technicians to embed a "trapdoor" microchip in PROMIS after acquiring the software through back channels from the DOJ, with the modified software then distributed internationally through British media proprietor [[Robert Maxwell]] and his Israeli computer firm [[Degem]].[^3]

Alleged foreign intelligence and law enforcement users of the backdoored PROMIS include agencies in [[Israel]], [[Canada]] (the [[Royal Canadian Mounted Police|RCMP]] and [[Canadian Security Intelligence Service|CSIS]]), the [[United Kingdom]], [[Australia]], [[South Korea]], [[Iraq]], [[Jordan]], [[Libya]], [[Poland]], [[South Africa]], and the [[Soviet Union]]. International financial institutions alleged to have received PROMIS-derived systems include BCCI, [[Banco Nazionale del Lavoro]], the [[HSBC|Hong Kong and Shanghai Banking Corporation]], [[UBS|Union Bank of Switzerland]], and [[Bank of America]]. Total sales through the Maxwell network were alleged to exceed $500 million.[^3][^4]

The [[Bua Report]] (1993) and a subsequent DOJ review (1994) found no credible evidence that enhanced PROMIS was distributed internationally, concluding that only public-domain versions of the software had been shared with foreign entities.[^1]

The witnesses central to the foreign-distribution claims were assessed as unreliable. Michael Riconosciuto was arrested on drug charges eight days after submitting his March 1991 backdoor affidavit and was later convicted of distributing methamphetamine, a conviction that figured in evaluations of his credibility. Earl Brian denied involvement in any PROMIS scheme and was never charged in connection with it, though he was separately convicted in 1996 of unrelated financial fraud involving the [[Financial News Network]] and [[United Press International]]. Commentators writing after the 2013 disclosures about [[National Security Agency]] bulk surveillance described PROMIS as a conceptual forerunner of mass data integration, while cautioning that the specific trapdoor-distribution narrative remained unproven and rested on the same contested witnesses the official reviews had rejected.[^5][^6][^7]

### Later Developments

In September 1987, Bankruptcy Judge George Francis Bason, Jr. ruled that DOJ had "taken, converted, stole" INSLAW's enhanced PROMIS. That ruling was affirmed by the D.C. Circuit Court in November 1989 but reversed on jurisdictional grounds by the Court of Appeals in May 1991. Bason had awarded INSLAW about 6.8 million dollars in damages, and he was not reappointed to the bankruptcy bench after his rulings against the department, an outcome the Hamiltons and congressional investigators viewed with suspicion; the district judge [[William Bryant]], upholding the findings in 1989, had described the support for them as convincing, perhaps compelling.

The House Judiciary Committee launched a three-year investigation from 1989 to 1992, producing House Report 102-857 on September 10, 1992, which found "strong evidence" of DOJ theft and raised "serious concerns" about a high-level conspiracy. The report was unclassified and publicly available. Special Counsel [[Nicholas J. Bua]], appointed in November 1991, issued a 267-page report in March 1993 finding no credible evidence of criminal wrongdoing by any DOJ official. The Senate referred INSLAW's remaining claims to the Court of Federal Claims, which ruled in 1997-1998 that all PROMIS versions were in the public domain.

Bill Hamilton maintained INSLAW's claims publicly for decades after the formal proceedings concluded. The international backdoor distribution allegations - particularly those concerning Rafael Eitan, Robert Maxwell, and Degem - were never formally adjudicated. A 2001 report alleged that FBI double agent [[Robert Hanssen]] provided PROMIS-derived software to his Soviet KGB handlers.[^1][^2]

### Footnotes

[^1]: U.S. Department of Justice. *Report of Special Counsel Nicholas J. Bua to the Attorney General of the United States Regarding the Allegations of Inslaw, Inc.* March 1993.
[^2]: U.S. House of Representatives, Committee on the Judiciary. *The INSLAW Affair: Investigative Report.* House Report 102-857, 102nd Congress, 2nd Session, September 10, 1992.
[^3]: Thomas, Gordon. *Gideon's Spies: The Secret History of the Mossad.* St. Martin's Press, 1999.
[^4]: Ben-Menashe, Ari. *Profits of War: Inside the Secret U.S.-Israeli Arms Network.* TrineDay, 1992.
[^5]: "The Deep, Meaningless Rabbithole of the Inslaw/PROMIS Affair," *Investigative Economics,* 2024, on Michael Riconosciuto's arrest eight days after his affidavit and his methamphetamine conviction. https://www.investigativeeconomics.org/p/the-deep-meaningless-rabbithole-of
[^6]: "Ex-Chief of Wire Service Convicted of Fraud Conspiracy," *The Washington Post,* October 1996, on Earl Brian's conviction for financial fraud involving the Financial News Network and United Press International. https://www.washingtonpost.com/archive/politics/1996/10/18/ex-chief-of-wire-service-convicted-of-fraud-conspiracy/314ff075-52fe-450b-8f47-b353898ccfe1/
[^7]: "PRISM's Controversial Forerunner," *Consortium News,* 2013, on PROMIS as a conceptual forerunner of bulk data integration and the unproven trapdoor narrative. https://consortiumnews.com/2013/07/11/prisms-controversial-forerunner/
[^8]: "The Mysterious Death of Danny Casolaro," *All That's Interesting,* on the August 1991 death, the missing notes, and the 2024 documentary *American Conspiracy: The Octopus Murders*. https://allthatsinteresting.com/danny-casolaro
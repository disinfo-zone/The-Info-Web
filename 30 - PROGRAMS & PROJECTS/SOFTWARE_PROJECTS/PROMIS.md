---
created: 2024-04-25
updated: 2025-01-03
title: PROMIS
tags:
  - PROMIS
  - INSLAW
  - Conspiracy
description: PROMIS, a case management software developed by INSLAW in the 1970s, faced controversy after being allegedly stolen by the U.S. Justice Department. It became central to conspiracy theories involving espionage, backdoors, and international proliferation, with ties to intelligence agencies and global criminal activities.
---
**PROMIS** (**Prosecutor's Management Information System**) was a pioneering case management software system developed in the 1970s and 80s by [[INSLAW|The Institute for Law and Social Research]] (INSLAW). The software was originally designed to help the [[U.S. Attorney's office]] in DC automate and streamline their case management processes. This expanded across the country and internationally. However, it later became embroiled in controversy, theft, and conspiracy theories.
## Origins and Development

In 1969, US Attorney [[Thomas A. Flannery]] perceived an urgent need for new techniques for dealing with the overwhelming amount of cases going through the [[U.S. Attorney's office|DC U.S. Attorney's Office]]. The [[Office of Crime Analysis of the District of Columbia]] (funded by the [[LEAA|Law Enforcement Assistance Administration]] (LEAA)) gave a $60,000 grant (70-DF-047) to [[Peat, Marwick, Mitchell & Co]] that put together a team of lawyers, management analysts, criminologists, statisticians, and computer science specialists to development a computer-based information system for the prosecutor.

This team was headed by [[Joan E. Jacoby]] (then Director of the [[Office of Crime Analysis of the District of Columbia]]) and [[Charles R. Work]] (then Deputy Chief of the Superior Court Division of the [[U.S. Attorney's office]]) with project manager [[Bill Hamilton]] (senior consultant at [[Peat, Marwick, Mitchell & Co]], formerly [[NSA]] analyst). Other team members included [[Sidney H. Brounstein]], [[Robert H. Cain]], [[Joyce H. Deroy]], [[James M. Etheridge]], [[John L. Gizzarelli]], [[Fred L. Lander III]], [[Soo Lee]], [[Dean C. Merrill]], [[John M. Middleton]], [[Stanley H. Turner]], [[Frederick G. Watts]], [[Dennis W. Wright]], and [[Robert Whitaker]]. 14 months were spent designing the system (NOTE: this timeline doesn’t work out properly).

The system came to be known as the Prosecutor's Management Information System (PROMIS) and deployed on January 1, 1971 in Washington D.C. for the District Attorney's Office. 

PROMIS had four basic subsystems: Report Generator, Forms Generator, Generalized Inquiry Package, Management Report Package. It could track case details, court schedules, witness information, and even “score” how important cases were (and later how likely someone was to commit another crime).

The software operated in batch processing mode (no online capabilities) and was designed to run on LEAA's [[IBM]] mainframe. It used a flat file database structure, and had no online data entry or inquiry capabilities. Original PROMIS was written in PL/I but was reprogrammed to COBOL for subsequent versions.

Around 1973 (date unclear), [[Bill Hamilton]] and [[Nancy Hamilton]] founded [[INSLAW|The Institute of Law and Social Research]], a non profit think tank that was to be the steward of the PROMIS software. The LEAA declared PROMIS an "exemplary project" and further funded INSLAW to enhance PROMIS to make it a transferrable system that could be adopted by other jurisdictions. The LEAA also funded "transfers" for municipalities to adopt the PROMIS software.

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
### PROMIS 82
> [!TODO] TODO
> Still determining the difference between PROMIS 82, VAX PROMIS, and DOJ lawsuit PROMIS
## Theft and Misappropriation by the U.S. Justice Department 

- In 1982, Inslaw signed a $10 million [[INSLAW contract|contract]] with the [[U.S. Department of Justice]] to install PROMIS in 42 U.S. Attorneys' offices as part of a pilot program
- The contract had vague and contradictory language in terms of deliverables, software ownership, and licensing rights
- The Justice Dept later tried to claim ownership of PROMIS, insisting its development was funded under the original contract
- High-level Justice Dept officials, including [[Lowell Jensen]], were allegedly involved in a scheme to bankrupt INSLAW by withholding payments and contractual disputes
- Under financial duress and legal pressure, INSLAW was forced to hand over the PROMIS source code to the Justice Dept to end the contract dispute 
- However, this gave the Justice Dept the ability to surreptitiously modify and distribute PROMIS both domestically and to foreign governments without INSLAW's knowledge or consent
- Key individuals within the Justice Dept who were allegedly involved in the theft and distribution of PROMIS later left to private sector positions where they continued to profit from the stolen software
- Ultimately concluded in [[Inslaw, Inc., et al. v. The United States]]

## Danny Casolaro and "The Octopus"
- Freelance reporter [[Danny Casolaro]] began investigating the [[PROMIS Software Scandal]] in 1990 after being contacted by [[INSLAW]] founder [[Bill Hamilton]].[1]
- Casolaro believed the theft of [[PROMIS]] was connected to a sprawling criminal conspiracy he termed "[[The Octopus]]", involving:
    - U.S. intelligence agencies, especially the [[Central Intelligence Agency|CIA]] and [[National Security Agency|NSA]][1]
    - International espionage and arms dealing[1]
    - Organized crime and drug cartels, especially those involved in the [[Iran-Contra Affair]][1]
    - Money laundering through [[Bank of Credit and Commerce International|BCCI]][1]
    - Covert operations to manipulate foreign governments[1]
- Casolaro was working on a book entitled "Behold, A Pale Horse," which encompassed these interconnected events.[1]
- Casolaro [[Death of Danny Casolaro|died under suspicious circumstances]] in August 1991 while investigating leads related to [[The Octopus]] and [[PROMIS]].[1]
- His death was ruled a suicide, but family and friends suspect foul play and a cover-up, noting that his research files on [[PROMIS]] and [[The Octopus]] were missing from his hotel room.[1]

## The "Backdoor" Theory and International Proliferation
- Numerous sources allege that U.S. intelligence agencies modified PROMIS with a secret [[backdoor]] before selling it to foreign governments and banks
- The backdoor allegedly allowed U.S. intelligence to surreptitiously access the databases of international PROMIS users and monitor their data in real-time 
- [[Michael Riconosciuto]], a self-proclaimed computer expert with ties to U.S. intelligence agencies, claims he was tasked with modifying PROMIS with the backdoor and [[artificial intelligence]] capabilities 
- Alleged international users of the backdoored PROMIS include:
    - [[Israel]]
    - [[Canada]] 
    - [[United Kingdom]] 
    - [[Australia]]
    - [[South Korea]]
    - [[Iraq]]
    - [[Libya]]
    - The [[Soviet Union]] and later [[Russia]]  
-  International banks alleged to have used the backdoored PROMIS include:
    - [[Bank of Credit and Commerce International|BCCI]] 
    - [[Banco Nazionale del Lavoro]]
    - [[HSBC|Hong Kong and Shanghai Banking Corporation (HSBC)]]
    - [[UBS|Union Bank of Switzerland (UBS)]]
    - [[Bank of America]]
-  [[Mossad]], Israel's intelligence service, is alleged to have played a key role in the international distribution of PROMIS as a favor to the [[Reagan administration]] 
- The backdoor would have essentially given U.S. intelligence agencies a window into the activities of foreign governments, banks, and international criminal and terrorist organizations
- The international proliferation of PROMIS, if true, represents an unprecedented breach of national sovereignty and privacy on a global scale

## Later Developments and Continuing Mysteries
- In 1987, a federal bankruptcy court ruled that the [[U.S. Department of Justice]] had indeed "stolen" PROMIS from [[INSLAW]], but that ruling was later overturned on appeal
-  Inslaw founder [[Bill Hamilton]] continues to maintain that PROMIS was fraudulently stolen from his company and distributed internationally, but has not been able to conclusively prove the [[backdoor]] theory in court
- In 1991, the U.S. House Judiciary Committee launched an investigation into the PROMIS affair, but its final report in 1992 was classified and its contents have never been fully revealed 
- In 1995, the [[NSA]] filed an affidavit in the PROMIS bankruptcy case claiming that some unspecified "national security" interests would be at risk if the case were allowed to proceed
- Alleged [[PROMIS]] derivatives and successors continue to be sold and used internationally for intelligence and data mining, but their connection to the original stolen version remains unclear
---
category: "Organizations"
tags:
  - Organization
  - IronMarch
  - NeoNazi
  - AtomwaffenDivision
  - SiegeCulture
  - Forum
  - Russia
  - DatabaseLeak
created: 2026-05-21
updated: 2026-05-22
summary: "Iron March was a Russian neo-fascist web forum founded by Alisher Mukhitdinov in 2011 that served as the primary incubator for Atomwaffen Division and several other neo-Nazi organizations until its closure in 2017, after which a 2019 database leak exposed 1,207 user accounts and enabled identification of military personnel, law enforcement employees, and organizational moderators across multiple countries."
start: 2011
end: 2017
location: "Russia (online)"
---

[[Iron March]] was a neo-fascist web forum founded in 2011 by [[Russia|Russian]] nationalist [[Alisher Mukhitdinov]] (operating under the alias "Alexander Slavros") and active until its closure in 2017. During its six years of operation, it served as the primary international incubator for a new generation of neo-Nazi and neo-fascist organizations, most significantly [[Atomwaffen Division]], and played a critical role in popularizing [[James Mason]]'s 1992 book *[[Siege]]* among a younger generation of online militants beginning in 2015.

### Founding and Character

Mukhitdinov launched Iron March in 2011 as an explicitly neo-fascist and neo-Nazi discussion community. The forum's character distinguished it from older white nationalist online spaces by its emphasis on international fascist solidarity rather than American white nationalism specifically, its embrace of philosophical and esoteric neo-Nazism alongside more conventional political content, and its willingness to host members from across the world who were organizing actual offline groups.

The forum attracted members who were simultaneously producing theory, building organizations, and planning operations, which made it unusually consequential relative to its size. Members who later committed acts of violence, founded violent organizations, or were prosecuted on terrorism-related charges had all been active participants in the Iron March community.

### Predecessor: International Third Positionist Federation

Iron March was not the forum's original identity. On June 26, 2010, an unidentified individual using the username "Kacen" created a forum called the "International Third Positionist Federation" (ITPF) on [[Bizhat]], an India-based hosting service offering ready-to-use forum templates. ITPF showed no activity until April 2011, when Mukhitdinov joined and began creating content. In September 2011, the ITPF administrators migrated the forum to a new domain, ironmarch.org, using [[Invision Power Services]] software, and shut down the ITPF instance. An Iron March moderator using the screen name "Woman in Black" referenced unspecified technical issues as the reason for migration in private messages recovered from the database. The identity of "Kacen" and of "Woman in Black" has not been established in open-source reporting.[^1]

### Forum Administration and Named Moderators

Mukhitdinov ("Alexander Slavros") is the only forum administrator whose real identity has been fully established. [[BBC News Russian]] identified Mukhitdinov in January 2020, following an investigation that located him still living in southwest Moscow in a prefabricated apartment block. His parents had met as students at the [[Moscow State Institute of International Relations]] (MGIMO), an institution with documented ties to Russian state security agencies. His father was a businessman and CEO of a charitable foundation. A close relative on his father's side, [[Nuritdin Mukhitdinov]], was a senior Soviet official who led the Uzbek government under Khrushchev and served as an ambassador. BBC Russia investigated claims that Alisher Mukhitdinov had been pressured by Russian authorities for alleged fundraising for the [[Azov Battalion]] (designated a terrorist organization in Russia) but found no evidence the fundraising occurred. He has not been prosecuted in any jurisdiction as of May 2026.[^2]

[[Benjamin Raymond]], the co-founder of [[National Action]], was a named Iron March administrator. Raymond's administrative role on Iron March predated National Action's founding in 2013, and he served as the organization's primary propagandist. The Iron March database confirmed Raymond's Iron March presence in records surfaced after the 2019 leak.[^3]

[[John Cartwright II]], operating under the username "Blood and Iron," joined Iron March in September 2011, immediately after the forum's founding, and served as a moderator. Database records and private message content identified him as a U.S. Navy member last known to be residing in Millersville, Maryland. He participated in Skype groups with other early-period Iron March members. His moderator role placed him within the core administrative cohort alongside Slavros from the forum's inception.[^4]

### Atomwaffen Division

The most significant organizational product of Iron March was [[Atomwaffen Division]], announced to the community on October 12, 2015 by founding member [[Brandon Russell]]. Russell had been organizing AWD for years before the formal announcement, claiming active recruitment since at least 2012, and AWD's ideological foundation in *Siege* and [[accelerationism]] reflected the content environment Iron March had cultivated.[^3]

The forum's 2015 rediscovery and promotion of *Siege* was the critical event in *Siege*'s resurgence as an influential text. James Mason's essays had been largely ignored since the 1992 compilation, but Iron March gave them a global neo-Nazi audience that included the membership base from which AWD recruited.[^5]

### Organizations Incubated by Iron March

Beyond Atomwaffen Division, the forum directly produced or provided the founding membership for:

[[National Action]] (UK, 2013): Founded by Benjamin Raymond (Iron March administrator) and [[Alex Davies]], who used the username "Daddy Terror" on Iron March. National Action was the first offline organization to emerge directly from Iron March and served as a model for subsequent formations.[^3]

[[Antipodean Resistance]] (Australia, October 2016): Founded by [[Tim Heibach]] (username "Xav") and announced to the Iron March community on October 10, 2016, encouraging Australian Iron March users to contact "Xav" and "Kehlsteinhaus." The Iron March database later exposed Heibach's real identity. Other identified founding-era members included [[Nathaniel Anderson]] (username "HalArts," also "Rusty Sandusky") and [[Jacob Hersant]].[^6]

### Database Leak: Technical Record

The Iron March SQL database was uploaded to the [[Internet Archive]] on November 6, 2019, by a user operating under the handle "antifa-data," implying an activist motivation. The leaker's identity has not been established in any public record. The Internet Archive removed the dataset shortly after it was posted, but torrent links published by [[Bellingcat]] kept it circulating among researchers and journalists.

The leaked archive contained a complete snapshot of the forum as it existed shortly before the site went offline in November 2017. Specific data fields included: member IDs, usernames, registration email addresses, IP addresses used at registration and login, registration timestamps (Unix format), two-factor authentication logs, all public forum posts, all private message threads (approximately 22,000 conversations), and forum administration data. The SQL dump required a database viewer such as MySQL Workbench or DB Browser for SQLite, but the same torrent included exported spreadsheets organized by field, lowering the technical barrier for non-specialist researchers.[^7]

The researcher operating under the handle "Jewish Worker" built an independent searchable website from the raw data, making the dump accessible to non-technical journalists and activists who could query usernames, email addresses, and post content without managing their own SQL environment.[^8]

Bellingcat published a how-to guide for accessing and interpreting the data on the same day as the leak, November 6, 2019, and separately produced an interactive map geolocating all forum activity originating from IP addresses near U.S. military installations. Bellingcat also compiled a spreadsheet of all private message threads involving users who identified themselves as active-duty military.[^7]

The [[MIT Media Lab]] undertook a computational analysis of the forum corpus using latent Dirichlet allocation (LDA) topic modeling and network analysis, finding that Iron March grew through social bonding rather than ideological convergence, a finding with implications for counter-extremism strategy.[^9]

### Forum Statistics and Geographic Distribution

At the time of its 2017 closure, Iron March had 1,207 registered user accounts. Those users produced more than 195,000 public posts and approximately 4,500 to 22,000 private message threads (sources vary in granularity). The median self-reported age of the user base was 26, and the average was 28, based on data from 183 users who disclosed their age.

Among the 1,185 accounts that did not mask their IP addresses with a VPN or proxy, the dominant geographic concentrations outside the English-speaking world were the Netherlands, Germany, Sweden, and Brazil. Within the English-speaking world, U.S.-based registrations dominated, followed by the [[United Kingdom]] (approximately 9 percent), [[Canada]] (approximately 7 percent), and [[Australia]] (approximately 5 percent).[^10]

### Verified Real-Name Mappings: Military and Government Personnel

The database leak directly enabled identification of active-duty military and government employees whose extremist activity had been pseudonymous. The following cases are documented in published investigative reporting:

[[David Cole Tarkington]] used the username "The Yank" and was active on Iron March from 2013 to 2016, at which point he was serving as an aviation machinist mate's apprentice with [[Strike Fighter Squadron VFA-41]] at [[Naval Air Station Lemoore]], California. Private message records showed he attempted to recruit at least 12 Iron March members into Atomwaffen Division. [[Gizmodo]] reporters identified him in March 2020 and notified the Navy. [[NCIS]] opened an investigation. Tarkington was administratively separated from the Navy in April 2020. No criminal charges were filed.[^11]

[[Travis Frey]] used the username "In Hoc Signo Vinces" and joined Iron March in 2013. He posted at least a dozen times between 2016 and 2017 while working as head of security at a [[CoreCivic]] jail in Indianapolis. By the time of his identification in January 2020, he had been promoted to captain at the [[Nevada Southern Detention Center]], a CoreCivic facility contracted with [[ICE]]. Database records included Frey's personal email address, phone number, birthday, and place of residence, enabling [[Vice News]] to identify him directly. Forum posts showed Frey describing himself as a "fascist" and expressing interest in organizing for the [[Traditionalist Workers Party]] in Indiana. CoreCivic placed him on administrative leave following Vice's January 2020 reporting. U.S. Senators called for a federal investigation into the Nevada facility.[^12]

[[Thomas Adam Guba]], using the username "22goy," registered with the email address tguba2004@hotmail.com, enabling his identification as a Navy employee at the [[Naval Medical Logistics Command]] in Baltimore, Maryland. His photograph appeared in the Naval Medical Logistics Command journal "Logistically Speaking" in its October-December 2017 issue, shortly after he had gone inactive on Iron March. Previously he had served as an aviation structural mechanic.[^13]

[[Van Ramsey Laws-Spencer]] was linked to two Iron March accounts: "Ozymandias" (registered with email pentaghast123@gmail.com, active October 2013 to April 2016) and "Turok" (email including Laws-Spencer's name, active August to October 2012). Multiple social media profiles operating under the "pentaghast123" username corroborated the identification. At the time of identification, Laws-Spencer was an active-duty Marine stationed at [[Camp Pendleton]], California.[^14]

[[Boris Mihajlovic]] posted on Iron March in 2016, encouraging other Canadian users to enlist in the armed forces for weapons training. [[CBC News]] identified him and confirmed he had been promoted to leading seaman in April 2018 and was working as a supply technician for [[HMCS Tecumseh]], a naval reserve establishment in Calgary. When contacted, Mihajlovic acknowledged the posts and stated he had left extremist activity behind.[^15]

### Verified Real-Name Mappings: Other Notable Identifications

[[Raivis Zeltits]], the Secretary-General of Latvia's [[National Alliance]] party from 2014 to 2020, was identified through the database on November 12, 2019, as the user "Latvian_Integralist." Zeltits acknowledged the account in a Facebook post, stating he had written those posts at age 20 and no longer held those views. He remained in contact with Iron March administrator Benjamin Raymond as late as 2015. The identification triggered calls for his resignation within Latvian political circles.[^16]

[[Benjamin Hannam]], a probationary constable with the [[Metropolitan Police Service]] (London), was identified through Iron March database records as a member of [[National Action]] before he applied to join the police. He had signed up to Iron March when he joined National Action's London branch in March 2016, more than two years before his police application. He was convicted on April 1, 2021 at the [[Old Bailey]] of National Action membership, two counts of fraud by false representation, two counts of possessing terrorist documents, and possession of a prohibited image of a child. He was sentenced to four years and four months, the first serving UK police officer convicted of terrorism-related offenses. The Iron March database was the mechanism through which his connection to National Action was first established.[^17]

[[Nicholas Waugh]] (username "HaggiSS"), a Scottish businessman from Aberdeenshire, was identified by a joint investigation by [[The Ferret]] and [[Daily Record]]. The database showed Waugh had attempted to order National Action stickers, messaged fascists in Lithuania, Bulgaria, and Australia to build international links, and encouraged members to attend demonstrations in the UK. He operated an Etsy shop named "Wodenstone" selling handcrafted traditional jewelry. He was identified as a significant figure in Scottish National Action and [[Scottish Dawn]] before proscription.[^18]

### Airbnb Platform Response

In December 2019, [[Airbnb]] cross-referenced its identity-verification database against the leaked Iron March member list and banned more than 60 confirmed Iron March users from the platform. All identified Iron March accounts on Airbnb had been guest accounts rather than host accounts.[^19]

### Successor Forum: Fascist Forge

In April 2018, approximately six months after Iron March's closure, a user operating under the name "Mathias" launched [[Fascist Forge]], explicitly described in a founding note as a replacement for Iron March intended to "continue where they left off." Fascist Forge replicated Iron March's vetting process, requiring prospective members to submit ideological essays before gaining full access. By February 2020 the forum had more than 1,500 registered users. Fascist Forge's hosting registrar took the site offline in February 2020. No strong successor consolidation forum emerged immediately, though the network's activity dispersed into encrypted messaging applications and alternative platforms.[^20]

### Footnotes

[^1]: CTC West Point. "The Iron March Forum and the Evolution of the 'Skull Mask' Neo-Fascist Network." https://ctc.westpoint.edu/the-iron-march-forum-and-the-evolution-of-the-skull-mask-neo-fascist-network/
[^2]: Meduza. "How a Moscow man from an Uzbek family started the world's biggest neo-Nazi forum." February 4, 2020. https://meduza.io/en/feature/2020/02/04/how-a-moscow-man-from-an-uzbek-family-started-the-world-s-biggest-neo-nazi-forum
[^3]: CTC West Point. "The Iron March Forum and the Evolution of the 'Skull Mask' Neo-Fascist Network." https://ctc.westpoint.edu/the-iron-march-forum-and-the-evolution-of-the-skull-mask-neo-fascist-network/
[^4]: Iron March Dossiers. "John Cartwright II, aka Blood and Iron, Moderator of Neo-Nazi Forum Iron March." March 13, 2020. https://ironmarch.noblogs.org/post/2020/03/13/john-cartwright-ii-moderator-of-neo-nazi-forum-iron-march/
[^5]: SPLC. "Atomwaffen Division." Extremist Files. https://www.splcenter.org/resources/extremist-files/atomwaffen-division/
[^6]: The White Rose Society. "Antipodean Resistance and the Lads Society." https://thewhiterosesociety.writeas.com/antipodean-resistance-and-the-lads-society; Times of Israel. "Antipodean Resistance: Australia's new Nazis." https://blogs.timesofisrael.com/antipodean-resistance-australias-new-nazis/
[^7]: Bellingcat. "Massive White Supremacist Message Board Leak: How to Access and Interpret the Data." November 6, 2019. https://www.bellingcat.com/resources/how-tos/2019/11/06/massive-white-supremacist-message-board-leak-how-to-access-and-interpret-the-data/
[^8]: Gizmodo. "Neo-Nazi Web Forum Iron March Has SQL Database Dumped on the Internet Archive." November 7, 2019. https://gizmodo.com/neo-nazi-web-forum-iron-march-has-sql-database-dumped-o-1839721580
[^9]: MIT Media Lab. "Investigating the Iron March Forums with Computational Tools: Far-Right Forum Network and LDA Analysis." Project overview, October 2020 to June 2023. https://www.media.mit.edu/projects/investigating-the-iron-march-forums-with-computational-tools-far-right-forum-network-and-lda-analysis/overview/
[^10]: Lawfare. "The Iron March Data Dump Provides a Window Into How White Supremacists Communicate and Recruit." https://www.lawfaremedia.org/article/iron-march-data-dump-provides-window-how-white-supremacists-communicate-and-recruit; CTC West Point. "The Iron March Forum and the Evolution of the 'Skull Mask' Neo-Fascist Network." https://ctc.westpoint.edu/the-iron-march-forum-and-the-evolution-of-the-skull-mask-neo-fascist-network/
[^11]: Gizmodo. "Leak Exposes U.S. Navy Sailor as Once-Prolific Recruiter for Neo-Nazi Group." March 12, 2020. https://gizmodo.com/leak-exposes-u-s-navy-sailor-as-once-prolific-recruite-1841149776; Newsweek. "Navy Kicks Out Alleged Recruiter for Neo-Nazi Group Atomwaffen Division After Investigation." April 2020. https://www.newsweek.com/navy-kicks-out-alleged-recruiter-neo-nazi-group-atomwaffen-division-after-investigation-1498704
[^12]: Vice. "ICE Detention Center Captain Was on a Neo-Nazi Website and Wanted to Start a White Nationalist Group." January 2020. https://www.vice.com/en/article/ice-detention-center-captain-was-on-a-neo-nazi-website-and-wanted-to-start-a-white-nationalist-group/; Vice. "ICE Detention Center Captain With Neo-Nazi Ties Was Just Placed on Leave." January 2020. https://www.vice.com/en/article/ice-detention-center-captain-with-neo-nazi-ties-was-just-placed-on-leave/
[^13]: Iron March Dossiers. "Thomas Adam Guba: Samuel Shapiro, Naval Medical Logistics Command Employee and Fascist Iron March User." February 27, 2020. https://ironmarch.noblogs.org/post/2020/02/27/thomas-adam-guba-naval-medical-logistics-command-member-and-fascist-iron-march-user/
[^14]: Iron March Dossiers. "Van Ramsey Laws-Spencer: Neo-Nazi Organizer on Iron March and Active Marine." March 4, 2020. https://ironmarch.noblogs.org/post/2020/03/04/van-ramsey-lawsspencer-neo-nazi-organizer-on-iron-march-and-active-marine/
[^15]: CBC News. "Leak of thousands of posts from defunct neo-Nazi forum offers clues to identify Canadian members." November-December 2019. https://www.cbc.ca/news/canada/iron-march-message-board-canadian-forces-1.5353201
[^16]: Baltic Word / LSM. "Latvian Senior National Alliance figure apologises." November 2019. https://eng.lsm.lv/article/politics/politics/senior-national-alliance-figure-apologises-for-cloud-of-far-right-messages.a338044/
[^17]: ITV News. "Neo-Nazi police officer Ben Hannam guilty of belonging to terror group National Action." April 1, 2021. https://www.itv.com/news/2021-04-01/neo-nazi-police-officer-ben-hannam-guilty-of-belonging-to-terror-group-national-action
[^18]: The Ferret. "Named: the Scots businessman linked to neo-Nazi groups." 2020. https://www.theferret.scot/neo-nazi-haggiss-iron-march/
[^19]: Gizmodo. "Airbnb Bans Over 60 White Supremacists After Iron March Forum Database Leak." December 2019. https://gizmodo.com/airbnb-bans-over-60-white-supremacists-after-iron-march-1840420392
[^20]: ADL. "Fascist Forge: A New Forum for Hate." https://www.adl.org/resources/article/fascist-forge-new-forum-hate; Vice. "Fascist Forge, the Online Neo-Nazi Recruitment Forum, Is Down." February 2020. https://www.vice.com/en_ca/article/43zn8j/fascist-forge-the-online-neo-nazi-recruitment-forum-is-down

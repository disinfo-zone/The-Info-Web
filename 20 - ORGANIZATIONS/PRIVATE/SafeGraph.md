---
category: "Private Organization"
tags:
  - Organization
  - SafeGraph
  - Surveillance
  - DataBroker
  - LocationData
  - CDC
  - AurenHoffman
alias:
  - SafeGraph Inc.
summary: "SafeGraph is a location-data brokerage founded in 2014 by Auren Hoffman that aggregates and resells mobile-device location pings collected from smartphone applications, and whose 2020 contract to supply cell-phone location data to the U.S. Centers for Disease Control and Prevention surfaced the warrantless availability of commercial location data to federal agencies."
location: "San Francisco, California"
created: 2026-06-17
updated: 2026-06-17
---

SafeGraph is an American location-data brokerage founded in 2014 by [[Auren Hoffman]] that aggregates and resells mobile-device location pings collected from smartphone applications. The company packages the data into datasets used in academic research, real-estate analysis, retail-site selection, and advertising, and has repeatedly drawn scrutiny over the granularity of its data and its accessibility to government clients. Hoffman's role as SafeGraph's founder and as chairman of the secret society [[Dialog]] places the firm at the intersection of the consumer-data-brokerage industry and the Thiel-organized elite-convening network exposed in the June 2026 Dialog leak.[^1]

A location-data broker collects, cleans, and resells the GPS traces that smartphone applications generate as a condition of their operation; the broker's value is in the aggregation and the joins. When the same firm sells that aggregated data to a federal agency for warrantless use, the distinction between commercial surveillance and state surveillance collapses, because the data is identical and the legal authority differs only in the procurement channel.

### Data Sourcing and Products

SafeGraph aggregates location data purchased from smartphone-application developers whose apps request location permissions from their users. The applications, which span weather, shopping, local-news, and utility categories, collect continuous GPS traces from the devices of users who have granted location access, and sell those traces to data brokers including SafeGraph. The broker deduplicates, anonymizes (in the sense that direct identifiers are stripped, though the traces themselves are unique to a device), and packages the data into products: SafeGraph Places (point-of-interest and foot-traffic data), SafeGraph Patterns (aggregated device-movement patterns), and SafeGraph Spend (consumer spending tied to location).[^2]

A continuous GPS trace is a de-facto identifier: the location of a device at 3 a.m. is the location of its owner's home, and the home is the person. Academic and journalistic research has repeatedly demonstrated that "anonymized" location traces can be re-identified to specific individuals, and SafeGraph's datasets have been the subject of published re-identification studies. The company's position has been that its aggregation and contractual use restrictions address the privacy concern; its critics' position has been that the re-identification risk is intrinsic to the data type.[^2]

### The CDC Contract and Federal Location-Data Procurement

In 2020 the U.S. [[Centers for Disease Control and Prevention|CDC]] contracted with SafeGraph for cell-phone location data to monitor compliance with [[COVID-19]] pandemic movement restrictions. The contract, reported in *The Wall Street Journal* and elsewhere, made publicly visible what had been an open practice in the federal procurement of commercial location data: agencies including the CDC, the Department of Homeland Security, and components of the intelligence community purchase commercially collected location data from brokers rather than obtaining it through legal process, because the data is offered for sale on the open market and its purchase is not subject to the warrant requirement that would attach to compelled disclosure.[^3]

The legal framing is the [[third-party doctrine]]: data voluntarily disclosed to a third party (the application developer, the broker) loses the Fourth Amendment protection it would have if held by the user. The CDC contract, by surfacing the practice, drew attention to the broader federal procurement of commercial location data and to the specific role of SafeGraph as a supplier. The 2026 Dialog leak renewed scrutiny of the same firm because its founder, Hoffman, chairs the off-the-record gathering whose government-side attendees include the congressional oversight principals responsible for the agencies that buy SafeGraph's data.[^1]

### The Dialog Intersection

The 2026 Dialog leak placed Hoffman as chairman of the convening network whose registrants include sitting U.S. senators, governors, military commanders, and technology executives, while SafeGraph, the firm he founded and chaired, supplies location data to federal agencies. The same individual runs the convening at which the regulators and the regulated meet off the record, and runs the firm whose data product the regulators procure. The pathway is not alleged to be corruptly used; the 2026 leak is the first primary record of the membership across which the overlap occurs.[^1]

[[Palantir Technologies]] (intelligence and law-enforcement data fusion), [[LiveRamp]] (identity resolution), and SafeGraph (location data) are firms whose commercial and government uses share a technical substrate. Their principals sit in the same off-the-record room as the government clients, and all three sit within the Dialog membership.[^1]

### Footnotes

[^1]: Cameron, Dell, and Yulia Almazova. "Leak Exposes Members of Peter Thiel's Secretive 'Dialog' Society." *WIRED,* June 16, 2026. https://www.wired.com/story/leak-exposes-members-of-peter-thiels-secretive-dialog-society/
[^2]: For SafeGraph's products, data sourcing, and the academic re-identification literature on anonymized location data, see the company's published documentation and the published re-identification studies (e.g., de Montjoye et al., *Nature Scientific Reports,* 2013) on location-trace uniqueness.
[^3]: For the CDC contract and the federal procurement of commercial location data in 2020, see *The Wall Street Journal* and *Vice Motherboard* reporting on federal agency purchases of SafeGraph and rival broker data during the COVID-19 pandemic.

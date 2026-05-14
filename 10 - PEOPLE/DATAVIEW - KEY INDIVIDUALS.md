---
tags:
  - MOC
  - META
---
# People Index

This is the master index for all people in The Info Web. Each category below is auto-generated using Dataview queries — pages are automatically included based on their `category` frontmatter field.

To recategorize someone, edit their page's frontmatter `category` field. To add a new category, create a new `MOC - [Category].md` file following the same pattern.

---

## Key Figures
Central figures in the U.S. government's investigations into psychic phenomena and remote viewing.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "10 - PEOPLE"
WHERE category = "Key Figures"
SORT file.name ASC
```

## Psychics & Remote Viewers
Individuals known for psychic abilities, remote viewing, or participation in psi research.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "10 - PEOPLE"
WHERE category = "Psychics & Remote Viewers"
SORT file.name ASC
```

## Scientists & Researchers
Physicists, biologists, parapsychologists, and other researchers.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "10 - PEOPLE"
WHERE category = "Scientists & Researchers"
SORT file.name ASC
```

## Skeptics & Critics
Magicians, scientists, and writers who debunk or criticize paranormal claims.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "10 - PEOPLE"
WHERE category = "Skeptics & Critics"
SORT file.name ASC
```

## Intelligence & Government
CIA, DIA, NSA officials, politicians, diplomats, arms dealers, and intelligence operatives.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "10 - PEOPLE"
WHERE category = "Intelligence & Government"
SORT file.name ASC
```

## Military
Military officers and defense officials.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "10 - PEOPLE"
WHERE category = "Military"
SORT file.name ASC
```

## PROMIS Scandal
Central figures in the PROMIS/INSLAW software scandal.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "10 - PEOPLE"
WHERE category = "PROMIS Scandal"
SORT file.name ASC
```

## Iran-Contra
Central figures in the Iran-Contra affair and October Surprise.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "10 - PEOPLE"
WHERE category = "Iran-Contra"
SORT file.name ASC
```

## BCCI Scandal
Central figures in the BCCI banking scandal.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "10 - PEOPLE"
WHERE category = "BCCI Scandal"
SORT file.name ASC
```

## Organized Crime
Mobsters, cartel leaders, and figures in international criminal networks.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "10 - PEOPLE"
WHERE category = "Organized Crime"
SORT file.name ASC
```

## Authors & Journalists
Writers and journalists covering intelligence, parapsychology, or related topics.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "10 - PEOPLE"
WHERE category = "Authors & Journalists"
SORT file.name ASC
```

## Philanthropists & Benefactors
Individuals who funded parapsychology research and related programs.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "10 - PEOPLE"
WHERE category = "Philanthropists & Benefactors"
SORT file.name ASC
```

## Law Enforcement & Legal
Police, detectives, prosecutors, lawyers, and judges.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "10 - PEOPLE"
WHERE category = "Law Enforcement & Legal"
SORT file.name ASC
```

## UFO & Anomalous Phenomena
Individuals central to UFO/UAP research and disclosure.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "10 - PEOPLE"
WHERE category = "UFO & Anomalous Phenomena"
SORT file.name ASC
```

## Nuclear Scientists & Programs
Scientists and officials central to nuclear weapons development and policy.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "10 - PEOPLE"
WHERE category = "Nuclear Scientists & Programs"
SORT file.name ASC
```

## World War II & Nazi Era
Figures from the WWII and Nazi era, including occultists.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "10 - PEOPLE"
WHERE category = "World War II & Nazi Era"
SORT file.name ASC
```

## Belgium Scandals
Figures involved in Belgian political and criminal scandals.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "10 - PEOPLE"
WHERE category = "Belgium Scandals"
SORT file.name ASC
```

## JFK Assassination
Figures connected to the assassination of President Kennedy.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "10 - PEOPLE"
WHERE category = "JFK Assassination"
SORT file.name ASC
```

## Uncategorized
People needing further categorization.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "10 - PEOPLE"
WHERE category = "Other"
SORT file.name ASC
```

---

## Stats

```dataview
TABLE length(rows) AS Count
FROM "10 - PEOPLE"
WHERE category
GROUP BY category
SORT length(rows) DESC
```

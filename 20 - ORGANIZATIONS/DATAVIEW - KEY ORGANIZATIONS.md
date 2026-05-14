---
tags:
  - MOC
  - META
---
# Organizations Index

This Map of Content (MOC) auto-generates index tables for all organizations in The Info Web using Dataview queries. Pages are automatically included based on their `category` frontmatter field.

To recategorize an organization, edit its page's frontmatter `category` field.

---

## U.S. Government
Federal agencies, military branches, law enforcement, and government offices of the United States.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "20 - ORGANIZATIONS"
WHERE category = "U.S. Government"
SORT file.name ASC
```

## Foreign Government
Intelligence agencies, political parties, military forces, and government bodies of other nations.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "20 - ORGANIZATIONS"
WHERE category = "Foreign Government"
SORT file.name ASC
```

## International Bodies
Multinational organizations and intergovernmental agencies.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "20 - ORGANIZATIONS"
WHERE category = "International Body"
SORT file.name ASC
```

## Paramilitary
Guerrilla groups, rebel armies, militias, and military factions.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "20 - ORGANIZATIONS"
WHERE category = "Paramilitary"
SORT file.name ASC
```

## Private Organizations
Corporations, banks, media outlets, research institutes, crime syndicates, and other non-governmental entities.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "20 - ORGANIZATIONS"
WHERE category = "Private Organization"
SORT file.name ASC
```

---

## Stats

```dataview
TABLE length(rows) AS Count
FROM "20 - ORGANIZATIONS"
WHERE category
GROUP BY category
SORT length(rows) DESC
```

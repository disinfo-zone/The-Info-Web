---
tags:
  - MOC
  - META
---
# Events Index

This Map of Content (MOC) auto-generates index tables for all events in The Info Web using Dataview queries. Pages are automatically included based on their `category` frontmatter field.

To recategorize an event, edit its page's frontmatter `category` field.

---

## Intelligence Scandals
Covert operations, espionage incidents, and political cover-ups.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "40 - EVENTS"
WHERE category = "Intelligence Scandal"
SORT file.name ASC
```

## Contra War
Events connected to the Nicaraguan Contra war, drug trafficking networks, and the Dark Alliance investigation.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "40 - EVENTS"
WHERE category = "Contra War"
SORT file.name ASC
```

## Major Conflicts
Wars, military operations, and armed conflicts.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "40 - EVENTS"
WHERE category = "Major Conflict"
SORT file.name ASC
```

## Terrorism
Terrorist attacks, hijackings, and mass casualty events.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "40 - EVENTS"
WHERE category = "Terrorism"
SORT file.name ASC
```

## Crime Investigations
Serial murders, child trafficking investigations, and criminal cases with government connections.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "40 - EVENTS"
WHERE category = "Crime Investigation"
SORT file.name ASC
```

## Diplomacy
International summits, conferences, and diplomatic events.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "40 - EVENTS"
WHERE category = "Diplomacy"
SORT file.name ASC
```

## Historical Phenomena
Unexplained events, paranormal incidents, and historical anomalies.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "40 - EVENTS"
WHERE category = "Historical Phenomenon"
SORT file.name ASC
```

## Modern Incidents
Recent UAP encounters, domestic incidents, and contemporary events.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "40 - EVENTS"
WHERE category = "Modern Incident"
SORT file.name ASC
```

---

## Stats

```dataview
TABLE length(rows) AS Count
FROM "40 - EVENTS"
WHERE category
GROUP BY category
SORT length(rows) DESC
```

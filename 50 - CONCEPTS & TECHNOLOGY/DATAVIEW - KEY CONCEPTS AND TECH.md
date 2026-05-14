---
tags:
  - MOC
  - META
---
# Concepts & Technology Index

This Map of Content (MOC) auto-generates index tables for all concepts and technologies in The Info Web using Dataview queries. Pages are automatically included based on their `category` frontmatter field.

To recategorize a concept, edit its page's frontmatter `category` field.

---

## Psi Phenomena
Psychic abilities, remote viewing, telepathy, and related phenomena.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "50 - CONCEPTS & TECHNOLOGY"
WHERE category = "Psi Phenomenon"
SORT file.name ASC
```

## Intelligence Concepts
Intelligence terminology, surveillance technologies, covert operations concepts, and espionage methods.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "50 - CONCEPTS & TECHNOLOGY"
WHERE category = "Intelligence Concept"
SORT file.name ASC
```

## Esoteric & Historical Concepts
Historical movements, social phenomena, and esoteric topics documented in the research.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "50 - CONCEPTS & TECHNOLOGY"
WHERE category = "Esoteric & Historical Concept"
SORT file.name ASC
```

## Nuclear Concepts
Nuclear weapons, proliferation, treaties, and related technologies.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "50 - CONCEPTS & TECHNOLOGY"
WHERE category = "Nuclear Concept"
SORT file.name ASC
```

## Advanced Human Technology
Enhanced human capabilities, psychotronic weapons, and synthetic telepathy.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "50 - CONCEPTS & TECHNOLOGY"
WHERE category = "Advanced Human Technology"
SORT file.name ASC
```

## Scientific Theories & Technologies
Physics theories, detection technologies, and scientific classification systems.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "50 - CONCEPTS & TECHNOLOGY"
WHERE category = "Scientific Theory & Technology"
SORT file.name ASC
```

## Research Methodologies
Remote viewing protocols, research approaches, and experimental methods.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "50 - CONCEPTS & TECHNOLOGY"
WHERE category = "Research Methodology"
SORT file.name ASC
```

## Psychology & Behavioral Science
Psychological conditions, mind control, and behavioral research.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "50 - CONCEPTS & TECHNOLOGY"
WHERE category = "Psychology & Behavioral Science"
SORT file.name ASC
```

## Military Technology
Weapons systems, military platforms, and defense technologies.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "50 - CONCEPTS & TECHNOLOGY"
WHERE category = "Military Technology"
SORT file.name ASC
```

## Information Systems
Software systems, databases, and information management technologies.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "50 - CONCEPTS & TECHNOLOGY"
WHERE category = "Information System"
SORT file.name ASC
```

## Drugs & Trafficking
Narcotics, drug trafficking networks, and substance-related concepts.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "50 - CONCEPTS & TECHNOLOGY"
WHERE category = "Drugs & Trafficking"
SORT file.name ASC
```

---

## Stats

```dataview
TABLE length(rows) AS Count
FROM "50 - CONCEPTS & TECHNOLOGY"
WHERE category
GROUP BY category
SORT length(rows) DESC
```

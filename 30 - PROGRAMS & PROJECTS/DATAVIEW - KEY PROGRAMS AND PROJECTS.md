---
tags:
  - MOC
  - META
---
# Programs & Projects Index

This Map of Content (MOC) auto-generates index tables for all programs and projects in The Info Web using Dataview queries. Pages are automatically included based on their `category` frontmatter field.

To recategorize a program, edit its page's frontmatter `category` field.

---

## Psi Research Programs
Government-funded programs investigating psychic phenomena, remote viewing, and parapsychology.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "30 - PROGRAMS & PROJECTS"
WHERE category = "Psi Research Program"
SORT file.name ASC
```

## Intelligence Operations
Covert operations, police investigations, and intelligence programs.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "30 - PROGRAMS & PROJECTS"
WHERE category = "Intelligence Operation"
SORT file.name ASC
```

## Historical Programs
Major historical research and development programs with lasting significance.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "30 - PROGRAMS & PROJECTS"
WHERE category = "Historical Program"
SORT file.name ASC
```

## Software Projects
Software development projects and related scandals.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "30 - PROGRAMS & PROJECTS"
WHERE category = "Software Project"
SORT file.name ASC
```

---

## Stats

```dataview
TABLE length(rows) AS Count
FROM "30 - PROGRAMS & PROJECTS"
WHERE category
GROUP BY category
SORT length(rows) DESC
```

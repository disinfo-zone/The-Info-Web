---
tags:
  - MOC
  - META
---
# Places Index

A geographic index of all places referenced in the vault, organized by type. Places include countries, cities, U.S. states, military installations, regions, and landmarks.

---
## Countries

Nation-states and sovereign territories referenced in intelligence and research contexts.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "60 - PLACES"
WHERE category = "Country"
SORT file.name ASC
```

---
## Cities

Cities and urban areas significant to documented operations and events.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "60 - PLACES"
WHERE category = "City"
SORT file.name ASC
```

---
## U.S. States

American states referenced in intelligence operations and research.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "60 - PLACES"
WHERE category = "U.S. State"
SORT file.name ASC
```

---
## Military Installations

Military bases, airfields, and defense facilities.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "60 - PLACES"
WHERE category = "Military Installation"
SORT file.name ASC
```

---
## Regions

Geographic regions and areas spanning multiple countries.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "60 - PLACES"
WHERE category = "Region"
SORT file.name ASC
```

---
## Landmarks

Specific buildings, sites, and locations of interest.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "60 - PLACES"
WHERE category = "Landmark"
SORT file.name ASC
```

---
## Stats

```dataview
TABLE length(rows) AS Count
FROM "60 - PLACES"
WHERE category
GROUP BY category
SORT length(rows) DESC
```

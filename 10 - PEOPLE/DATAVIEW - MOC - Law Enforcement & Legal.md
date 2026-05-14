---
tags:
  - MOC
  - META
---
# Law Enforcement & Legal

Police, detectives, prosecutors, lawyers, and judges involved in related cases.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "10 - PEOPLE"
WHERE category = "Law Enforcement & Legal"
SORT file.name ASC
```

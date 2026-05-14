---
tags:
  - MOC
  - META
---
# Military

Military officers and defense officials.

```dataview
TABLE WITHOUT ID
  file.link AS Name,
  summary AS Description
FROM "10 - PEOPLE"
WHERE category = "Military"
SORT file.name ASC
```

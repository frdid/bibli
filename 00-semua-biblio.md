## Semua
---
```dataview
TABLE
	WITHOUT ID string(creator) AS "Kreator",
	publish_date.year AS "Tahun",
	link(file.link, title) AS "Fail",
	platform AS "Platform"
FROM "04-Bibli"
WHERE !contains(file.name, "00-")
SORT creator ASC
SORT publish_date DESC
SORT rows.file.links
```





## Berdasarkan Kreator
---
```dataview
TABLE
	date(rows.file.frontmatter.publish_date).year AS "Tahun",
	link(rows.file.link, rows.file.frontmatter.title) AS "Fail"
FROM "04-Bibli"
WHERE !contains(file.name, "00-")
GROUP BY creator AS "Kreator"
```

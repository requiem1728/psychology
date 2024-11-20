---
type: course
aliases: "{"
---
## In progress
**status:** ==wip== *(work in progress)*
```dataview
TABLE WITHOUT ID	file.link AS "Name",	url,	category AS "Cathegory"FROM !"templates"WHERE type = "course" AND status = "wip"
```
## Waiting
**status:** ==todo==
```dataview
TABLE WITHOUT ID	file.link AS "Name",	url,	category AS "Cathegory" FROM !" templates"WHERE type = "course" AND status = "todo"
```
## Already done
**status:** ==done==
```dataview
TABLE WITHOUT ID	file.link AS "Name",	url,	category AS "Cathegory" FROM !"templates"WHERE type = "course" AND status = "done"
```

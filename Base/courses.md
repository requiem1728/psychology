---
type: course
aliases: "{"
---
## В процессе
**status:** ==wip== *(work in progress)*
```dataview
TABLE WITHOUT ID	file.link AS "Name",	url,	category AS "Cathegory"FROM !"templates"WHERE type = "course" AND status = "wip"
```
## Ожидают прохождения
**status:** ==todo==
```dataview
TABLE WITHOUT ID	file.link AS "Name",	url,	category AS "Cathegory" FROM !" templates"WHERE type = "course" AND status = "todo"
```
## Завершённые
**status:** ==done==
```dataview
TABLE WITHOUT ID	file.link AS "Name",	url,	category AS "Cathegory" FROM !"templates"WHERE type = "course" AND status = "done"
```

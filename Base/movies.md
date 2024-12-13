---
type: movie
aliases: "%"
---
%%cssClass: cards%%
## In progress
**status:** ==wip== *(work in progress)*
```dataview
TABLE WITHOUT ID	
("![|80](" + cover + ")") as "Cover",	file.link AS "Name",	
author AS "Director",	
category AS "Cathegory"
FROM !"templates"
WHERE type = "movie" AND status = "wip"
```
## Waiting
**status:** ==todo==
```dataview
TABLE WITHOUT ID	
("![|80](" + cover + ")") as "Cover",	file.link AS "Name",
director AS "Director",
category AS "Cathegory"
FROM !"templates"
WHERE type = "movie" AND status = "todo"
```
## Already done
**status:** ==done==
```dataview
TABLE WITHOUT ID	
("![|80](" + cover + ")") as "Cover",	file.link AS "Name",	
director AS "Director",
category AS "Cathegory"
FROM !"templates"
WHERE type = "movie" AND status = "done"
```

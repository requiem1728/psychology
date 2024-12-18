---
type: movie
aliases: "%"
---
%%cssClass: cards%%
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

---
type: book
aliases:
  - '"&"'
---
%%cssClass: cards%%
## In progress
**status:** ==wip== *(work in progress)*
```dataview
TABLE WITHOUT ID	
("![|80](" + cover + ")") as "Cover",	file.link AS "Name",	author AS "Author(s)",	start AS "Started",	category AS "Cathegory"
FROM !"templates"
WHERE type = "book" AND status = "wip"
```

## To be read
**status:** ==todo==
```dataview
TABLE WITHOUT ID	
("![|80](" + cover + ")") as "Cover",	file.link AS "Name",	author as "Author(s)",	recommendedby AS "Recommended by",	category AS "Cathegory"FROM !"templates"WHERE type = "book" AND status = "todo"
```
## Already read
**status:** ==done==
```dataview
TABLE WITHOUT ID	
("![|80](" + cover + ")") as "Cover",	file.link AS "Name",	author AS "Author(s)",	start AS "Started",	end AS "Ended",	category AS "Cathegory"
FROM !"templates"WHERE type = "book" AND status = "done"
````


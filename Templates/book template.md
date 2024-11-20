---
type: book
aliases:
  - "& <%* tR += title %>"
cover: "{{coverUrl}}"
start: 
end: 
status: 
recommendedby:
---

<%*
let title = tp.file.title
if (title.startsWith("Untitled")) {
title = await tp.system.prompt("Title");
}
await tp.file.rename(title)
-%>

___
tags::
prev:: [[books|назад в библиотеку]]
category::
author:: [[{{author}}]]
children::
___
PDF
![cover|150]({{coverUrl}}
___
<% tp.file.cursor(0) %>


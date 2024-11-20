<% "---" %>
<%*
let title = tp.file.title
if (title.startsWith("Untitled"))
{
title = await tp.system.prompt("Title");
}
await tp.file.rename(title)
-%>
type: book
aliases:
  - '- "& <%* tR += title %>"'
cover: "{{coverUrl}}"
start: 
end: 
status: todo
recommendedby:
<% "---" %>

---
tags ::
prev :: 📚 [[books | back to library]]
category ::
author ::👨 [[{{author}}]]
children ::

---
PDF
![cover|150]({{coverUrl}})

---

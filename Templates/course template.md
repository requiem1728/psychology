<% "---" %>
<%*
let title = tp.file.title
if (title.startsWith("Untitled"))
{
title = await tp.system.prompt("Title");
}
await tp.file.rename(title)
-%>
type: course
aliases: 
- - "{ <%* tR += title %>"
status: todo
<% "---" %>

---
tags::
prev:: [[courses | back to library]]
category::
url::
children::

---


<% tp.file.cursor(0) %>

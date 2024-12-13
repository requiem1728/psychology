<% "---" %>
<%*let title = tp.file.title
if (title.startsWith("Untitled")) {
title = await tp.system.prompt("Title");
}
await tp.file.rename(title)
-%>---
type: movie
aliases:
- - "% <%* tR += title %>"
cover: {{VALUE:Poster}}
status: todo
recommendedby:
<% "---" %>
___tags:: prev:: [[movies|back to library]]
category::
author:: {{VALUE:directorLink}}
children::
___
![cover|150]({{VALUE:Poster}})
___
<% tp.file.cursor(0) %>

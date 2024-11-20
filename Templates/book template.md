---
type: book
aliases: - "& <%* tR += title %>"
cover: {{coverUrl}}
start:
end:
status: todo
recommendedby:
---
<%*
  let title = tp.file.title
  if (title.startsWith("Untitled")) {
    title = await tp.system.prompt("Title");
    await tp.file.rename(`${title}`);
  } 
  tR += "---"
%>
tags: Note <%tp.file.creation_date("YYYY")%>
---
# <%* tR += `${title}` %>

<% tp.file.cursor() %>

___

## References:
- 

---
creation date:: [[<%tp.file.creation_date("YYYY-MM-DD")%>]] <%tp.file.creation_date("HH:mm")%>


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


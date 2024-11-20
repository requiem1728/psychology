---
type: book
aliases:
  - "& <%* tR += title %>"
cover: http://books.google.com/books/content?id=Cr0iAwAAQBAJ&printsec=frontcover&img=1&zoom=1&edge=curl&source=gbs_api
start: 2024-11-20
end: 
status: todo
recommendedby: Obsidian
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
author:: [[David H. Barlow]]
children::
___
PDF
![cover|150](http://books.google.com/books/content?id=Cr0iAwAAQBAJ&printsec=frontcover&img=1&zoom=1&edge=curl&source=gbs_api
___
<% tp.file.cursor(0) %>
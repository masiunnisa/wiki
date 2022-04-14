---
created: <%tp.date.now()%>
title: <%tp.file.title%>
tags:
  - note
---

<% tp.file.move("/inbox/" + tp.file.title) %>
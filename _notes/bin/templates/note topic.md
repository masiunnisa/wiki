---
title: <% tp.file.title %>
created: <% tp.date.now() %>
---

- Topic: [[<% tp.file.cursor(1) %>]]

***

<% tp.file.move("/inbox/" + tp.file.title) %>
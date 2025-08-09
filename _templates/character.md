---
<%*
let alignment = ""
title = await tp.system.prompt("Alignment")
-%>
tags:
  - character
date: <% tp.date.now("DD-MM-YYYY", -1) %>
alignment: <% alignment %>
---
<%*
let title = ""
title = await tp.system.prompt("Name")
await tp.file.rename(title) 
-%>

| **Appearance**            | **Profession**(s) | **Locations** | **Relations** |
| ------------------------- | ----------------- | ------------- | ------------- |
| Specie:<br>Hair: <br>Eyes |                   |               |               |

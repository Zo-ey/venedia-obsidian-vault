---
tags:
  - location
date: <% tp.date.now("DD-MM-YYYY", -1) %>
map: false
owner:
---
<%*
let title = ""
title = await tp.system.prompt("Name")
await tp.file.rename(title) 
-%>
# Map

# Quests


```dataview
LIST
FROM #quest 
WHERE destination-loc = this.file.name
```


# Information
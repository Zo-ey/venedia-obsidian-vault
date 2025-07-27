---
<%*
let dest = ""
let title = ""
title = await tp.system.prompt("Title")
dest = await tp.system.prompt("Destination")
await tp.file.rename(title)
-%>
tags:
  - quest
creation-date: <% tp.date.now("DD-MM-YYYY", -1) %>
fc-calendar: Calendar of Harptos
fc-date: <% Calendarium.getAPI("Calendar of Harptos").getCurrentDate().year + "-" + Calendarium.getAPI("Calendar of Harptos").getCurrentDate().month+1 + "-" + Calendarium.getAPI("Calendar of Harptos").getCurrentDate().day %>
fc-end:
destination-loc: <% dest %>
status: false
---

| **Source** | **Destination(s)** location | **Task(s)** | **Promised reward** |
| ---------- | --------------------------- | ----------- | ------------------- |
|            |          <% dest %>          |             |                     |
# Description

# Evenements
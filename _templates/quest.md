---
<%*
let dest = ""
dest = await tp.system.prompt("Destination") 
-%>
tags:
  - quest
creation-date: <% tp.date.now("DD-MM-YYYY", -1) %>
fc-calendar: Calendar of Harptos
fc-date: <% Calendarium.getAPI("Calendar of Harptos").getCurrentDate().year + "-" + Calendarium.getAPI("Calendar of Harptos").getCurrentDate().month+1 + "-" + Calendarium.getAPI("Calendar of Harptos").getCurrentDate().day %>
fc-end:
destination-loc: <% dest %>
---

| **Source** | **Destination(s)** location | **Task(s)** | **Promised reward** |
| ---------- | --------------------------- | ----------- | ------------------- |
|            |          <% dest %>          |             |                     |
# Description

# Evenements
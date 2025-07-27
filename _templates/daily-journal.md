---
tags:
creation-date: <% tp.date.now("DD-MM-YYYY", -1) %>
fc-calendar: Calendar of Harptos
fc-date: <% Calendarium.getAPI("Calendar of Harptos").getCurrentDate().year + "-" + Calendarium.getAPI("Calendar of Harptos").getCurrentDate().month+1 + "-" + Calendarium.getAPI("Calendar of Harptos").getCurrentDate().day %>
fc-end:
---

<%*
let title = Calendarium.getAPI("Calendar of Harptos").getCurrentDate().year + "-" + Calendarium.getAPI("Calendar of Harptos").getCurrentDate().month+1 + "-" + Calendarium.getAPI("Calendar of Harptos").getCurrentDate().day
await tp.file.rename(title) 
-%>
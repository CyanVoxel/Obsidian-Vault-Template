---
date: <%tp.date.now("YYYY-MM-DD")%>T<%tp.date.now("HH:mm")%>
tags:
  - Daily
cssclasses:
  - daily
  - <%*
const dayOfWeek = tp.date.now("dd");
if (dayOfWeek == "Mo")
{
%>monday<%*
}
else if (dayOfWeek == "Tu")
{
%>tuesday<%*
}
else if (dayOfWeek == "We")
{
%>wednesday<%*
}
else if (dayOfWeek == "Th")
{
%>thursday<%*
}
else if (dayOfWeek == "Fr")
{
%>friday<%*
}
else if (dayOfWeek == "Sa")
{
%>saturday<%*
}
else if (dayOfWeek == "Su")
{
%>sunday<%*
}
%>
---
# DAILY NOTE
## <%tp.date.now("dddd, MMMM Do, YYYY")%>
***
### Journal
#### TIME
Customize this template to your liking!
...
***
### Tasks
- [ ] Task 1
- [ ] Task 2
- [ ] Task 3
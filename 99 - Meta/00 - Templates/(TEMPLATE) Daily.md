---
date: <% moment(tp.file.title,'YYYY-MM-DD').format("dddd, MMMM DD, YYYY") %>
tags:
  - Daily
cssclasses:
  - daily
  <% "- " + moment(tp.file.title,'YYYY-MM-DD').format("dddd, MMMM DD, YYYY").toLowerCase() %>
---
# DAILY NOTE
## <% moment(tp.file.title,'YYYY-MM-DD').format("dddd, MMMM DD, YYYY") %>
***
### Journal
#### TIME
Customiza esta plantilla a tu gusto.
...
***
### Tareas
- [ ] Tarea 1
- [ ] Tarea 2
- [ ] Tarea 3

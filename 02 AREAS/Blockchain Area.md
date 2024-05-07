---
tags:
  - area
Links: "[[My Areas]]"
---
## Projects
### Not Started 🔴
```dataview
table Status, Fecha_Inicio, Fecha_Entrega
from [[]] AND #project 
where contains(Status, "🔴")
```
### In Progress 🟠
```dataview
table Status, Fecha_Inicio, Fecha_Entrega
from [[]] AND #project 
where contains(Status, "🟠")
```
### Finished 🟢
```dataview
table Status, Fecha_Inicio, Fecha_Entrega
from [[]] AND #project 
where contains(Status, "🟢")
```



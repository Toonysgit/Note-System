## By Last Modified
```dataview
list
from "04 ARCHIVOS"
sort file.mtime desc
```

```dataview
LIST WITHOUT ID item.text
FROM #resource AND #clase
FLATTEN file.lists as item
WHERE contains(item.tags, "#rolimper_ip")
SORT date DESC 
```


```query
line:(🌱)
```

---
alias: city
name: Ank'Harel
continent: Marquet
---

# The Oasis City

#place #city #ankharel

Ank'Harel seems to be an oasis city located in the continent of Marquet. It has many different districts, many temples, colleges and other areas of study, commerce and people. It also has some interesting creatures, they call **camels**.

![Ank'Harel map](Ank'Harel.webp)

## Known residents
```dataview
TABLE organisations as "Organisations"
from #npc
WHERE location="Ank'Harel"
SORT file.name ASC
```

## Known locations
```dataview
LIST summary
FROM #place 
WHERE location="Ank'Harel"
SORT file.name ASC
```

## Known organisations
```dataview
LIST
FROM #organisation 
WHERE location="Ank'Harel"
SORT file.name ASC
```
---
Location: Town of Vallaki
---


````columns
id: DY4-PboKSX1SrusL8wUo1
===
```dataview
Table WITHOUT ID file.link AS "NPCs at this Location"
from "NPCs/NPC Files/PlayerNPCFiles"
Where Location = this.Location
```
===
```dataview
Table WITHOUT ID file.link AS "Places in this Location"
from "Locations/Places"
Where Location = this.Location
```
````


![[Town Of Vallaki Map]]



---
Location:
type: Location
KnownByParty: False
---

````columns
id: <% tp.date.now("DDMMMMYYYYHHmmss") %>

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







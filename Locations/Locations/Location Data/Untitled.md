---
Location:
type: Location
KnownByParty:False
---

5th September 2025 17:16:33

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







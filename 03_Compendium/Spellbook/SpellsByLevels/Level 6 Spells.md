---
tags:
  - Spell
---
```dataview
TABLE SpellLevel, MPCost, CastingMethod, Range, CastingTime, Duration
From "Spells/All Spells"
WHERE SpellLevel = 6
Sort SpellLevel ASC

```
sort file.name ASC

WHERE contains(file.tags, "#Bard")
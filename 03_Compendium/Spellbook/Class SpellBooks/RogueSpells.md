---
tags:
  - Spell
  - Rogue
---
```dataview
TABLE SpellLevel, MPCost, CastingMethod, Range, CastingTime, Duration
From ""
WHERE contains(file.tags, "#Rogue") and contains(file.tags, "#Spell") and MPCost > 1
Sort SpellLevel ASC

```

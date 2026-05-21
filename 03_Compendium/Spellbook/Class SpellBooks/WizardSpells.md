---
tags:
  - Spell
  - Wizard
---
```dataview
TABLE SpellLevel, MPCost, CastingMethod, Range, CastingTime, Duration
From ""
WHERE contains(file.tags, "#Wizard") and contains(file.tags, "#Spell") and MPCost > 1
Sort SpellLevel ASC

```

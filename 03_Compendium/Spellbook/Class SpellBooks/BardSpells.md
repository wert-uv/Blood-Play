---
tags:
  - Spell
  - Bard
---
TABLE SpellLevel, MPCost, CastingMethod, Range, CastingTime, Duration
From "Spells/All Spells"
WHERE contains(file.tags, "#Bard")+
Sort SpellLevel ASC

```dataview
TABLE SpellLevel, MPCost, CastingMethod, Range, CastingTime, Duration
From ""
WHERE contains(file.tags, "#Bard") and contains(file.tags, "#Spell") and MPCost > 1
Sort SpellLevel ASC

```
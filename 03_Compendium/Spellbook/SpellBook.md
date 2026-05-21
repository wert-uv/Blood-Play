```datacards
TABLE  SpellCover, MPCost, CastingMethod, Range, CastingTime, Duration
from "" 
WHERE contains(file.tags, "#Spell") and MPCost > 1
Sort file.name ASC
// Settings
preset: square
imageProperty: SpellCover
columns: 2

```


---
type: pc
race: "Humanoid (drow, elf, wizard)"
class:
 - "Galsariad Ardyth (Tier 2)"
subClass:
 - "CR 5"
cover: "Galsariad Ardyth (Tier 2).png"
campaign:
locations:
tags:
  - race/drow
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/crcotn
---
###### Galsariad Ardyth (Tier 2)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Galsariad Ardyth (Tier 2).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (drow, elf, wizard) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 67 (15d8) |
> | :FasUserGroup: Race | Humanoid (drow, elf, wizard) |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 14 | 10 | 18 | 15 | 12 |
| **Mod** | -1 | +2 | +0 | +4 | +2 | +1 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 12
**Languages:** Common, Draconic, Undercommon
**Saving Throws:** Int +7, Wis +5
**Skills:** Arcana +7, Investigation +7, Nature +7

---

### Traits

**Fey Ancestry.** Galsariad has advantage on saving throws against being charmed, and magic can't put him to sleep.


---

### Actions

**Drain Potential.** Melee or Ranged Spell Attack: +7 to hit, reach 5 ft. or range 60 ft., one creature. *Hit:* 22 (4d10) necrotic damage, and Galsariad gains 5 temporary hit points.

**Gravity Wave (Recharge 5–6).** Galsariad causes a rippling wave of magical gravity to fill a 20-foot-radius sphere centered on a point he can see within 100 feet of himself. Each creature in that area must make a DC 15 Strength saving throw. On a failed saving throw, the creature takes 35 (10d6) force damage and is pulled up to 20 feet toward the sphere's center, and is knocked prone. On a successful save, the creature takes half as much damage and isn't pulled or knocked prone.


---

### Bonus Actions

**Distort Gravity (1/Day).** Galsariad targets himself or one willing creature that he can see within 60 feet of himself, magically distorting gravity around the target. Any creature within 5 feet of the target takes 7 (2d6) force damage. In addition, the target can use a reaction to float upward, up to 20 feet, without provoking opportunity attacks. When this effect ends at the start of Galsariad's next turn, the target floats gently down up to 20 feet.


---

> [!column|flex 3]
>> [!important]- QUESTS:
>> ```base
>> properties:
>>   file.name:
>>     displayName: Name
>> views:
>>   - type: table
>>     name: Name
>>     filters:
>>       and:
>>         - file.inFolder("Compendium/Party/Quests")
>>         - file.hasLink(this.file)
>>     order:
>>       - file.name
>> ```
>
>> [!note]- HISTORY
>> ```base
>> properties:
>>   file.name:
>>     displayName: Name
>> views:
>>   - type: table
>>     name: Session Notes
>>     filters:
>>       and:
>>         - file.inFolder("Session Notes")
>>         - file.hasLink(this.file)
>> ```
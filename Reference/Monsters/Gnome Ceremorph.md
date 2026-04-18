---
type: pc
race: "Aberration"
class:
 - "Gnome Ceremorph"
subClass:
 - "CR 5"
cover: "Gnome Ceremorph.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/small
  - cr/5
  - source/idrotf
---
###### Gnome Ceremorph
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Gnome Ceremorph.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Small Aberration |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (breastplate) |
> | :FasHeart: HP | 58 (13d6 + 13) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 14 | 12 | 19 | 17 | 17 |
| **Mod** | -2 | +2 | +1 | +4 | +3 | +3 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** Deep Speech, Gnomish, telepathy 120 ft., Undercommon
**Saving Throws:** Int +7, Wis +6, Cha +6
**Skills:** Arcana +7, Deception +6, Insight +6, Perception +6, Persuasion +6, Stealth +5

---

### Traits

**Magic Resistance.** The ceremorph has advantage on saving throws against spells and other magical effects.


---

### Actions

**Tentacles.** Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. *Hit:* 15 (2d10 + 4) psychic damage. If the target is Medium or smaller, it is grappled (escape DC 9) and must succeed on a DC 15 Intelligence saving throw or be stunned until this grapple ends.

**Extract Brain.** Melee Weapon Attack: +7 to hit, reach 5 ft., one incapacitated humanoid grappled by the ceremorph. *Hit:* 55 (10d10) piercing damage. If this damage reduces the target to 0 hit points, the ceremorph kills the target by extracting and devouring its brain.

**Laser Pistol.** Ranged Weapon Attack: +5 to hit, range 40/120 ft., one target. *Hit:* 12 (3d6 + 2) radiant damage.

**Mind Blast (Recharge 5–6).** The ceremorph magically emits psychic energy in a 60-foot cone. Each creature in that area must succeed on a DC 15 Intelligence saving throw or take 22 (4d8 + 4) psychic damage and be stunned for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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
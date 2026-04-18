---
type: pc
race: "Celestial"
class:
 - "Bariaur Wanderer"
subClass:
 - "CR 3"
cover: "Bariaur Wanderer.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/medium
  - cr/3
  - source/mpp
---
###### Bariaur Wanderer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Bariaur Wanderer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Celestial |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 14 (studded leather) |
> | :FasHeart: HP | 71 (11d8 + 22) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 15 | 11 | 15 | 10 |
| **Mod** | +4 | +2 | +2 | +0 | +2 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Celestial, Common
**Saving Throws:** Str +6, Dex +4
**Skills:** Athletics +6, Perception +4, Stealth +4, Survival +6

---

### Traits

**Portal Sense.** The bariaur can sense the presence of portals within 30 feet of itself, including inactive portals, and instinctively knows the destination of each one. The bariaur knows the distance and direction to the last portal it used as long as they're on the same plane.


---

### Actions

**Multiattack.** The bariaur makes two Barbed Javelin or Shortbow attacks.

**Barbed Javelin.** Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 9 (1d10 + 4) piercing damage. If the target is a creature, its speed is reduced by 10 feet until the start of the bariaur's next turn.

**Ram.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) bludgeoning damage. If the bariaur moved at least 20 feet straight toward the target immediately before the hit, the target takes an extra 10 (3d6) bludgeoning damage, and the target must succeed on a DC 14 Strength saving throw or have the prone condition.

**Shortbow.** Ranged Weapon Attack: +4 to hit, range 80/320 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage, plus 4 (1d8) piercing damage if the target doesn't have all its hit points.


---

### Bonus Actions

**Mighty Leap.** The bariaur jumps a distance up to its walking speed.


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
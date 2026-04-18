---
type: pc
race: "Aberration"
class:
 - "Memory Web"
subClass:
 - "CR 4"
cover: "Memory Web.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/4
  - source/qftis
---
###### Memory Web
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: QftIS
___

> [!infobox|no-t right]
> ![[Memory Web.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 39 (6d10 + 6) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | QftIS |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 18 | 13 | 14 | 14 | 3 |
| **Mod** | +3 | +4 | +1 | +2 | +2 | -4 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (can't see beyond this radius), passive Perception 12
**Languages:** —
**Damage Resistances:** fire
**Condition Immunities:** blinded; deafened

---

### Traits

**Damage Transfer.** While it is grappling a creature, the memory web takes only half the damage dealt to it, and the creature grappled by the web takes the other half.

**False Appearance.** If the memory web is motionless at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the memory web move or act, that creature must succeed on a DC 18 Intelligence (Investigation) check to discern that the memory web is animate.

**Memory Flood.** When the memory web is reduced to 0 hit points, it discharges any memories it consumed over the past 24 hours in a telepathic deluge. Hazy, dreamlike visions of these discharged memories lodge in the minds of creatures up to 120 feet from the memory web.


---

### Actions

**Ensnare.** Melee Weapon Attack: +5 to hit, reach 5 ft., one Large or smaller creature. *Hit:* The target has the grappled condition (escape DC 13). Until this grapple ends, the target has the restrained condition and takes 7 (1d8 + 3) bludgeoning damage at the start of each of its turns. The memory web can grapple only one creature at a time.


---

### Bonus Actions

**Drain Memories.** The memory web targets one creature grappled by it. The target must make a DC 12 Intelligence saving throw. Constructs, Oozes, Plants, and Undead succeed on the save automatically. On a failed save, the target takes 5 (2d4) psychic damage and becomes memory drained until it finishes a long rest or the memory web is destroyed.
While memory drained, the target must roll a d4 each time it makes an ability check or attack roll, subtracting the d4 roll from it. Each time the target is memory drained beyond the first, the die size increases by one: the d4 becomes a d6, the d6 becomes a d8, and so on until the die becomes a d20, at which point the target has the unconscious condition for 1 hour. If a memory drained creature is the target of the Greater Restoration or Heal spell, the memory drained effect ends on it. On a successful save, the target takes half as much damage only.


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
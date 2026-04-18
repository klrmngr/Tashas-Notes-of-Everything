---
type: pc
race: "Humanoid (elf)"
class:
 - "Drow of Lolth"
subClass:
 - "CR 1/4"
cover: "Drow of Lolth.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-4
  - source/fraif
---
###### Drow of Lolth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Drow of Lolth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 13 (3d8) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 10 | 11 | 11 | 12 |
| **Mod** | +0 | +2 | +0 | +0 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 12
**Languages:** Common, Elvish, Undercommon
**Skills:** Perception +2, Stealth +4

---

### Traits

**Fey Ancestry.** The drow has Advantage on saving throws it makes to avoid or end the Charmed condition, and magic can't put the drow to sleep.

**Sunlight Sensitivity.** While in sunlight, the drow has Disadvantage on attack rolls.


---

### Actions

**Rapier.** m +4, reach 5 ft. *Hit:* 6 (1d8 + 2) Piercing damage.

**Drow Hand Crossbow.** r +4, range 30/120 ft. *Hit:* 4 (1d4 + 2) Piercing damage, and the target makes a saving throw. con DC 12.  The target has the Poisoned condition for 1 hour. If the target fails the save by 5 or more, it also has the Unconscious condition while Poisoned in this way. The target wakes up if it takes damage or if a creature within 5 feet of it takes an action to wake it.


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
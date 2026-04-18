---
type: pc
race: "Humanoid (elf)"
class:
 - "Drow Elite Warrior of Lolth"
subClass:
 - "CR 5"
cover: "Drow Elite Warrior of Lolth.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/fraif
---
###### Drow Elite Warrior of Lolth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Drow Elite Warrior of Lolth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 71 (11d8 + 22) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 18 | 14 | 11 | 13 | 12 |
| **Mod** | +1 | +4 | +2 | +0 | +1 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 14
**Languages:** Common, Elvish, Undercommon
**Saving Throws:** Dex +7, Con +5, Wis +4
**Skills:** Perception +4, Stealth +10

---

### Traits

**Fey Ancestry.** The drow has Advantage on saving throws it makes to avoid or end the Charmed condition, and magic can't put the drow to sleep.

**Sunlight Sensitivity.** While in sunlight, the drow has Disadvantage on attack rolls.


---

### Actions

**Multiattack.** The drow makes two attacks using Shortsword or Drow Hand Crossbow in any combination

**Shortsword.** m +7, reach 5 ft. *Hit:* 11 (2d6 + 4) Piercing damage plus 10 (3d6) Poison damage.

**Drow Hand Crossbow.** r +7, range 30/120 ft. *Hit:* 7 (1d6 + 4) Piercing damage, and the target makes a saving throw. con DC 15.  The target has the Poisoned condition for 1 hour. While Poisoned in this way, the target also has the Unconscious condition. The target wakes up if it takes damage or if a creature within 5 feet of it takes an action to wake it.


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
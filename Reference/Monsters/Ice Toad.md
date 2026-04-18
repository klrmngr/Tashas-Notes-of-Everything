---
type: pc
race: "Monstrosity"
class:
 - "Ice Toad"
subClass:
 - "CR 1"
cover: "Ice Toad.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/1
  - source/rot
---
###### Ice Toad
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Rise of Tiamat
___

> [!infobox|no-t right]
> ![[Ice Toad.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 12 (natural armor) |
> | :FasHeart: HP | 32 (5d8 + 10) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Rise of Tiamat |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 10 | 14 | 8 | 10 | 6 |
| **Mod** | +1 | +0 | +2 | -1 | +0 | -2 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Ice Toad
**Skills:** Perception +2
**Damage Immunities:** cold

---

### Traits

**Amphibious.** The toad can breathe air or water.

**Cold Aura.** Any creature that starts its turn within 5 feet of the toad takes 3 (1d6) cold damage.

**Standing Leap.** The toad's long jump is up to 20 feet and its high jump is up to 10 feet, with or without a running start.


---

### Actions

**Bite.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 4 (1d8) cold damage. If the target is a Medium or smaller creature it is grappled (escape DC 11). Until this grapple ends, the toad can't bite another target.


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
---
type: pc
race: "Beast"
class:
 - "Giant Walrus"
subClass:
 - "CR 4"
cover: "Giant Walrus.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/huge
  - cr/4
  - source/idrotf
---
###### Giant Walrus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Giant Walrus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Huge Beast |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 9 |
> | :FasHeart: HP | 85 (9d12 + 27) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 9 | 16 | 3 | 11 | 4 |
| **Mod** | +6 | -1 | +3 | -4 | +0 | -3 |

**Speed:** 20 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** —

---

### Traits

**Hold Breath.** The walrus can hold its breath for 30 minutes.


---

### Actions

**Multiattack.** The walrus makes two attacks: one with its body flop and one with its tusks.

**Body Flop.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 15 (2d8 + 6) bludgeoning damage.

**Tusks.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 16 (3d6 + 6) piercing damage.


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
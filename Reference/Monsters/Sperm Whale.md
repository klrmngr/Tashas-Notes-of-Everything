---
type: pc
race: "Beast"
class:
 - "Sperm Whale"
subClass:
 - "CR 8"
cover: "Sperm Whale.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/gargantuan
  - cr/8
  - source/idrotf
---
###### Sperm Whale
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Sperm Whale.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Gargantuan Beast |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 189 (14d20 + 42) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 8 | 17 | 3 | 12 | 5 |
| **Mod** | +8 | -1 | +3 | -4 | +1 | -3 |

**Speed:** 0 ft., swim 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft., passive Perception 11
**Languages:** —

---

### Traits

**Echolocation.** The whale can't use its blindsight while deafened.

**Hold Breath.** The whale can hold its breath for 90 minutes.

**Keen Hearing.** The whale has advantage on Wisdom (Perception) checks that rely on hearing.


---

### Actions

**Multiattack.** The whale makes two attacks: one with its bite and one with its tail.

**Bite.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 21 (3d8 + 8) piercing damage. If the target is a Large or smaller creature, it must succeed on a DC 14 Dexterity saving throw or be swallowed by the whale. A swallowed creature has 3 against attacks and other effects outside the whale, and it takes 3 (1d6) acid damage at the start of each of the whale's turns. If the whale takes 30 damage or more on a single turn from a creature inside it, the whale must succeed on a DC 16 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall prone in a space within 10 feet of the whale. If the whale dies, a swallowed creature can escape from the corpse by using 20 feet of movement, exiting prone.

**Tail.** Melee Weapon Attack: +11 to hit, reach 15 ft., one target. *Hit:* 18 (3d6 + 8) bludgeoning damage, or 37 (6d6 + 16) bludgeoning damage if the target is an object.


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
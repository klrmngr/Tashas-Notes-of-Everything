---
type: pc
race: "Ooze"
class:
 - "Bag Jelly"
subClass:
 - "CR 1"
cover: "Bag Jelly.png"
campaign:
locations:
tags:
  - race/ooze
  - affinity/hostile
  - type/ooze
  - size/medium
  - cr/1
  - source/bgg
---
###### Bag Jelly
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Bag Jelly.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Ooze |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 8 |
> | :FasHeart: HP | 42 (5d8 + 20) |
> | :FasUserGroup: Race | Ooze |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 6 | 19 | 2 | 7 | 2 |
| **Mod** | +1 | -2 | +4 | -4 | -2 | -4 |

**Speed:** 10 ft., climb 10 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (can't see beyond this radius), passive Perception 8
**Languages:** —
**Damage Resistances:** acid; bludgeoning
**Condition Immunities:** exhaustion

---

### Traits

**Amorphous.** The bag jelly can move through a space as narrow as 1 inch without squeezing.


---

### Actions

**Multiattack.** The bag jelly makes two Pseudopod attacks.

**Pseudopod.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 8 (2d6 + 1) acid damage. If the target is a Medium or smaller creature, it has the grappled condition (escape DC 11). Ability checks made to escape this grapple have disadvantage.


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
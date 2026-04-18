---
type: pc
race: "Construct"
class:
 - "Iron Defender"
subClass:
 - "CR 1"
cover: "Iron Defender.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/1
  - source/erlw
---
###### Iron Defender
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Iron Defender.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 30 (4d8 + 12) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 16 | 8 | 11 | 7 |
| **Mod** | +3 | +2 | +3 | -1 | +0 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** understands the languages of its creator but can't speak
**Skills:** Perception +4, Stealth +4
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Keen Senses.** The defender has advantage on Wisdom (Perception) checks.

**Telepathic Bond.** While the defender is on the same plane of existence as its master, it can magically convey what it senses to its master, and the two can communicate telepathically.


---

### Actions

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage. If the target is a creature, it must succeed on a DC 13 Strength saving throw or take an extra 3 (1d6) piercing damage and be grappled (escape DC 13). The defender can have only one creature grappled in this way at a time.


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
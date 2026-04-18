---
type: pc
race: "Giant (cloud giant)"
class:
 - "Blagothkus"
subClass:
 - "CR 9"
cover: "Blagothkus.png"
campaign:
locations:
tags:
  - race/cloud giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/9
  - source/hotdq
---
###### Blagothkus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Hoard of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Blagothkus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Huge Giant (cloud giant) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (splint armor) |
> | :FasHeart: HP | 138 (12d12 + 60) |
> | :FasUserGroup: Race | Giant (cloud giant) |
> | :FasBook: Source | Hoard of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 13 | 20 | 16 | 15 | 15 |
| **Mod** | +8 | +1 | +5 | +3 | +2 | +2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common, Draconic, Giant
**Saving Throws:** Con +9, Wis +6, Cha +6
**Skills:** Arcana +7, Insight +6, Intimidation +6, Perception +6

---

### Traits

**Keen Smell.** Blagothkus has advantage on Wisdom (Perception) checks that rely on smell.


---

### Actions

**Multiattack.** Blagothkus attacks twice with his morningstar.

**Morningstar.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 21 (3d8 + 8) piercing damage.


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
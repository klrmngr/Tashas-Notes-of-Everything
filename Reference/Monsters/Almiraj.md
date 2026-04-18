---
type: pc
race: "Beast"
class:
 - "Almiraj"
subClass:
 - "CR 0"
cover: "Almiraj.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/small
  - cr/0
  - source/toa
---
###### Almiraj
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tomb of Annihilation
___

> [!infobox|no-t right]
> ![[Almiraj.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Small Beast |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 3 (1d6) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Tomb of Annihilation |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 2 | 16 | 10 | 2 | 14 | 10 |
| **Mod** | -4 | +3 | +0 | -4 | +2 | +0 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 30 ft., passive Perception 14
**Languages:** —
**Skills:** Perception +4, Stealth +5

---

### Traits

**Keen Senses.** The almiraj has advantage on Wisdom (Perception) checks that rely on hearing or sight.

**Familiar.** With the DM's permission, the find familiar spell can summon an almiraj.


---

### Actions

**Horn.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage.


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
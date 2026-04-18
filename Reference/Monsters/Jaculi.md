---
type: pc
race: "Beast"
class:
 - "Jaculi"
subClass:
 - "CR 1/2"
cover: "Jaculi.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/large
  - cr/1-2
  - source/toa
---
###### Jaculi
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tomb of Annihilation
___

> [!infobox|no-t right]
> ![[Jaculi.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Large Beast |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 16 (3d10) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Tomb of Annihilation |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 14 | 11 | 2 | 8 | 3 |
| **Mod** | +2 | +2 | +0 | -4 | -1 | -4 |

**Speed:** 30 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., passive Perception 11
**Languages:** —
**Skills:** Athletics +4, Perception +1, Stealth +4

---

### Traits

**Camouflage.** The jaculi has advantage on Dexterity (Stealth) checks made to hide.

**Keen Smell.** The jaculi has advantage on Wisdom (Perception) checks that rely on smell.


---

### Actions

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 9 (2d6 + 2) piercing damage.

**Spring.** The jaculi springs up to 30 feet in a straight line and makes a bite attack against a target within its reach. This attack has advantage if the jaculi springs at least 10 feet. If the attack hits, the bite deals an extra 7 (2d6) piercing damage.


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
---
type: pc
race: "Monstrosity"
class:
 - "Guardian Wolf"
subClass:
 - "CR 4"
cover: "Guardian Wolf.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/huge
  - cr/4
  - source/egw
---
###### Guardian Wolf
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Explorer's Guide to Wildemount
___

> [!infobox|no-t right]
> ![[Guardian Wolf.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Huge Monstrosity |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 66 (7d12 + 21) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Explorer's Guide to Wildemount |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 14 | 16 | 5 | 12 | 8 |
| **Mod** | +6 | +2 | +3 | -3 | +1 | -1 |

**Speed:** 60 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common, Elvish
**Skills:** Perception +5, Stealth +4

---

### Traits

**Keen Hearing and Smell.** The wolf has advantage on Wisdom (Perception) checks that rely on hearing or smell.

**Pack Tactics.** The wolf has advantage on attack rolls against a creature if at least one of the wolf's allies is within 5 feet of the creature and the ally isn't incapacitated.


---

### Actions

**Multiattack.** The wolf makes two attacks: one with its bite and one with its claws.

**Bite.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 11 (1d10 + 6) piercing damage. If the target is a creature, it must succeed on a DC 16 Strength saving throw or be knocked prone.

**Claws.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 15 (2d8 + 6) piercing damage.


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
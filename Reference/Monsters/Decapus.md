---
type: pc
race: "Monstrosity"
class:
 - "Decapus"
subClass:
 - "CR 4"
cover: "Decapus.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/4
  - source/ttp
---
###### Decapus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: TTP
___

> [!infobox|no-t right]
> ![[Decapus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 75 (10d10 + 20) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | TTP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 14 | 14 | 4 | 10 | 7 |
| **Mod** | +2 | +2 | +2 | -3 | +0 | -2 |

**Speed:** 15 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** —
**Skills:** Athletics +4, Perception +2, Stealth +4

---

### Actions

**Multiattack.** The decapus makes two attacks: one with its bite and one with its tentacles.

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one creature grappled by the decapus. *Hit:* 7 (2d4 + 2) piercing damage.

**Tentacles.** Melee Weapon Attack: +4 to hit, reach 10 ft., one target. *Hit:* 24 (9d4 + 2) bludgeoning damage or 14 (5d4 + 2) bludgeoning damage if the decapus is grappling a creature other than the target or if the decapus is on the ground or floor. The target is also grappled (escape DC 14) unless the decapus is already grappling a creature. Until this grapple ends, the target is restrained.


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
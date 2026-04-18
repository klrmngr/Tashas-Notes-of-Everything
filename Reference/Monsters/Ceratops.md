---
type: pc
race: "Monstrosity (dinosaur)"
class:
 - "Ceratops"
subClass:
 - "CR 9"
cover: "Ceratops.png"
campaign:
locations:
tags:
  - race/dinosaur
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/9
  - source/bgg
---
###### Ceratops
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Ceratops.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity (dinosaur) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 139 (9d20 + 45) |
> | :FasUserGroup: Race | Monstrosity (dinosaur) |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 8 | 21 | 4 | 10 | 7 |
| **Mod** | +7 | -1 | +5 | -3 | +0 | -2 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** —

---

### Traits

**Magic Resistance.** The ceratops has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The ceratops makes one Gore attack and one Stomp attack.

**Gore.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 29 (4d10 + 7) piercing damage. If the ceratops moved at least 20 feet in a straight line toward the target immediately before the hit, the target takes an extra 11 (2d10) piercing damage; if the target is a creature, it also must succeed on a DC 19 Strength saving throw or be pushed up to 20 feet from the ceratops and have the prone condition.

**Stomp.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 29 (4d10 + 7) bludgeoning damage.


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
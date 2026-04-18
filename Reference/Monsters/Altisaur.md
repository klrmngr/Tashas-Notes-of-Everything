---
type: pc
race: "Monstrosity (dinosaur)"
class:
 - "Altisaur"
subClass:
 - "CR 13"
cover: "Altisaur.png"
campaign:
locations:
tags:
  - race/dinosaur
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/13
  - source/bgg
---
###### Altisaur
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Altisaur.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity (dinosaur) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 198 (12d20 + 72) |
> | :FasUserGroup: Race | Monstrosity (dinosaur) |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 28 | 6 | 23 | 3 | 12 | 7 |
| **Mod** | +9 | -2 | +6 | -4 | +1 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 21
**Languages:** —
**Skills:** Perception +11

---

### Traits

**Magic Resistance.** The altisaur has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The altisaur makes one Stomp attack and one Tail attack. The altisaur can't make both attacks against the same target.

**Stomp.** Melee Weapon Attack: +14 to hit, reach 10 ft., one target. *Hit:* 33 (7d6 + 9) bludgeoning damage. If the target is a Huge or smaller creature, it must succeed on a DC 22 Strength saving throw or have the prone condition.

**Tail.** Melee Weapon Attack: +14 to hit, reach 20 ft., one target. *Hit:* 45 (8d8 + 9) bludgeoning damage, and the target is pushed up to 20 feet horizontally from the altisaur.


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
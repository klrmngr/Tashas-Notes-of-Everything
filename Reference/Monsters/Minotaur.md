---
type: pc
race: "Monstrosity"
class:
 - "Minotaur"
subClass:
 - "CR 3"
cover: "Minotaur.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/3
  - source/mm
---
###### Minotaur
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Minotaur.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 76 (9d10 + 27) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 11 | 16 | 6 | 16 | 9 |
| **Mod** | +4 | +0 | +3 | -2 | +3 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 17
**Languages:** Abyssal
**Skills:** Perception +7

---

### Traits

**Charge.** If the minotaur moves at least 10 feet straight toward a target and then hits it with a gore attack on the same turn, the target takes an extra 9 (2d8) piercing damage. If the target is a creature, it must succeed on a DC 14 Strength saving throw or be pushed up to 10 feet away and knocked prone.

**Labyrinthine Recall.** The minotaur can perfectly recall any path it has traveled.

**Reckless.** At the start of its turn, the minotaur can gain advantage on all melee weapon attack rolls it makes during that turn, but attack rolls against it have advantage until the start of its next turn.


---

### Actions

**Greataxe.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 17 (2d12 + 4) slashing damage.

**Gore.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) piercing damage.


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
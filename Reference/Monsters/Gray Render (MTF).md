---
type: pc
race: "Monstrosity"
class:
 - "Gray Render"
subClass:
 - "CR 12"
cover: "Gray Render.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/12
  - source/mtf
---
###### Gray Render
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Gray Render.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 189 (18d10 + 90) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 13 | 20 | 3 | 6 | 8 |
| **Mod** | +4 | +1 | +5 | -4 | -2 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** —
**Saving Throws:** Str +8, Con +9
**Skills:** Perception +2

---

### Actions

**Multiattack.** The gray render makes three attacks: one with its bite and two with its claws.

**Bite.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 17 (2d12 + 4) piercing damage. If the target is Medium or smaller, the target must succeed on a DC 16 Strength saving throw or be knocked prone.

**Claws.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 13 (2d8 + 4) slashing damage. If the target is prone an additional 7 (2d6) bludgeoning damage is dealt to the target.


---

### Reactions

**Bloody Rampage.** When the gray render takes damage, it makes one attack with its claws against a random creature within its reach, other than its master.


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
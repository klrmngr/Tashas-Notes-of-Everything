---
type: pc
race: "Monstrosity"
class:
 - "The Lost"
subClass:
 - "CR 7"
cover: "The Lost.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/7
  - source/mtf
---
###### The Lost
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[The Lost.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 78 (12d8 + 24) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 12 | 15 | 6 | 7 | 5 |
| **Mod** | +3 | +1 | +2 | -2 | -2 | -3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 8
**Languages:** Common
**Skills:** Athletics +6
**Damage Resistances:** bludgeoning, piercing, slashing while in dim light or darkness

---

### Actions

**Multiattack.** The Lost makes two arm spike attacks.

**Arm Spike.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 14 (2d10 + 3) piercing damage.

**Embrace.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 25 (4d10 + 3) piercing damage, and the target is grappled (escape DC 14) if it is a Medium or smaller creature. Until the grapple ends, the target is frightened, and it takes 27 (6d8) psychic damage at the end of each of its turns. The Lost can embrace only one creature at a time.


---

### Reactions

**Tightening Embrace.** If the Lost takes damage while it has a creature grappled, that creature takes 18 (4d8) psychic damage.


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
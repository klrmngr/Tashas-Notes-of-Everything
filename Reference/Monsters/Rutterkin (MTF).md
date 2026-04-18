---
type: pc
race: "Fiend (demon)"
class:
 - "Rutterkin"
subClass:
 - "CR 2"
cover: "Rutterkin.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/2
  - source/mtf
---
###### Rutterkin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Rutterkin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Fiend (demon) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 37 (5d8 + 15) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 15 | 17 | 5 | 12 | 6 |
| **Mod** | +2 | +2 | +3 | -3 | +1 | -2 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 11
**Languages:** understands Abyssal but can't speak
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Crippling Fear.** When a creature that isn't a demon starts its turn within 30 feet of three or more rutterkins, it must make a DC 11 Wisdom saving throw. The creature has disadvantage on the save if it's within 30 feet of six or more rutterkins. On a successful save, the creature is immune to the Crippling Fear of all rutterkins for 24 hours. On a failed save, the creature becomes frightened for 1 minute. While frightened in this way, the creature is restrained. At the end of each of the frightened creature's turns, it can repeat the saving throw, ending the effect on itself on a success.


---

### Actions

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 12 (3d6 + 2) piercing damage. If the target is a creature, it must succeed on a DC 13 Constitution saving throw against disease or become poisoned. At the end of each long rest, the poisoned target can repeat the saving throw, ending the effect on itself on a success. If the target is reduced to 0 hit points while poisoned in this way, it dies and instantly transforms into a living [[Abyssal Wretch]]. The transformation of the body can be undone only by a wish spell.


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
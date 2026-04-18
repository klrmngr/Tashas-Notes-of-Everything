---
type: pc
race: "Monstrosity"
class:
 - "Hoard Scarab"
subClass:
 - "CR 1/8"
cover: "Hoard Scarab.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/tiny
  - cr/1-8
  - source/ftd
---
###### Hoard Scarab
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Hoard Scarab.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Tiny Monstrosity |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 7 (3d4) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 4 | 16 | 11 | 3 | 8 | 6 |
| **Mod** | -3 | +3 | +0 | -4 | -1 | -2 |

**Speed:** 20 ft., burrow 20 ft., fly 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., tremorsense 60 ft., passive Perception 9
**Languages:** —

---

### Traits

**False Appearance.** If the scarab is motionless at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the scarab move or act, that creature must succeed on a DC 18 Intelligence (Investigation) check to discern that the scarab is animate.


---

### Actions

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage. If the target is a creature, it has disadvantage on attack rolls until the start of its next turn.


---

### Bonus Actions

**Scale Dust (1/Day).** The scarab releases magical glittering dust from its wings. Each creature within 5 feet of the scarab must succeed on a DC 13 Dexterity saving throw or be outlined in blue light for 10 minutes. While outlined in this way, a creature sheds dim light in a 10-foot radius and can't benefit from being invisible. In addition, every Dragon within 1 mile of the creature becomes aware of it and can unerringly track the creature. Casting dispel magic on the creature ends the effect on it.


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
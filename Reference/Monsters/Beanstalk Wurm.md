---
type: pc
race: "Monstrosity"
class:
 - "Beanstalk Wurm"
subClass:
 - "CR 18"
cover: "Beanstalk Wurm.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/18
  - source/mcv4ec
---
###### Beanstalk Wurm
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV4EC
___

> [!infobox|no-t right]
> ![[Beanstalk Wurm.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 18 (20,000 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 231 (14d20 + 84) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | MCV4EC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 18 | 22 | 4 | 14 | 10 |
| **Mod** | +8 | +4 | +6 | -3 | +2 | +0 |

**Speed:** 50 ft., climb 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** —
**Saving Throws:** Str +14, Con +12

---

### Traits

**False Appearance.** If the wurm is motionless at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the wurm move or act, that creature must succeed on a DC 18 Intelligence (Investigation) check to discern that the wurm is animate.

**Leafy Handholds.** Creatures have advantage on ability checks made to climb the wurm.

**Legendary Resistance (3/Day).** If the wurm fails a saving throw, it can choose to succeed instead.

**Regeneration.** The wurm regains 20 hit points at the start of its turn if it has at least 1 hit point. If the wurm takes fire or lightning damage, this trait doesn't function at the start of the wurm's next turn.


---

### Actions

**Multiattack.** The wurm makes two Bite attacks.

**Bite.** Melee Weapon Attack: +14 to hit, reach 15 ft., one target. *Hit:* 30 (5d8 + 8) piercing damage. If the target is a Large or smaller creature, it must succeed on a DC 22 Dexterity saving throw or be swallowed by the wurm. A swallowed creature has the restrained condition, has 3 against attacks and other effects outside the wurm, and takes 28 (8d6) piercing damage at the start of each of the wurm's turns from thorns in the wurm's gullet.
The wurm's stomach can hold up to two creatures at a time. If the wurm takes 30 damage or more on a single turn from a creature inside it, the wurm must succeed on a DC 22 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, each of which falls in a space within 10 feet of the wurm and has the prone condition. If the wurm dies, a swallowed creature no longer has the restrained condition and can escape from the corpse by using 10 feet of movement, exiting with the prone condition.


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
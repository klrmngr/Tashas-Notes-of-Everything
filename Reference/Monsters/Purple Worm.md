---
type: pc
race: "Monstrosity"
class:
 - "Purple Worm"
subClass:
 - "CR 15"
cover: "Purple Worm.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/15
  - source/mm
---
###### Purple Worm
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Purple Worm.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 247 (15d20 + 90) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 28 | 7 | 22 | 1 | 8 | 4 |
| **Mod** | +9 | -2 | +6 | -5 | -1 | -3 |

**Speed:** 50 ft., burrow 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., tremorsense 60 ft., passive Perception 9
**Languages:** —
**Saving Throws:** Con +11, Wis +4

---

### Traits

**Tunneler.** The worm can burrow through solid rock at half its burrow speed and leaves a 10-foot-diameter tunnel in its wake.


---

### Actions

**Multiattack.** The worm makes two attacks: one with its bite and one with its stinger.

**Bite.** Melee Weapon Attack: +14 to hit, reach 10 ft., one target. *Hit:* 22 (3d8 + 9) piercing damage. If the target is a Large or smaller creature, it must succeed on a DC 19 Dexterity saving throw or be swallowed by the worm. A swallowed creature is blinded and restrained, it has 3 against attacks and other effects outside the worm, and it takes 21 (6d6) acid damage at the start of each of the worm's turns.
If the worm takes 30 damage or more on a single turn from a creature inside it, the worm must succeed on a DC 21 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall prone in a space within 10 feet of the worm. If the worm dies, a swallowed creature is no longer restrained by it and can escape from the corpse by using 20 feet of movement, exiting prone.

**Tail Stinger.** Melee Weapon Attack: +14 to hit, reach 10 ft., one creature. *Hit:* 19 (3d6 + 9) piercing damage, and the target must make a DC 19 Constitution saving throw, taking 42 (12d6) poison damage on a failed save, or half as much damage on a successful one.


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
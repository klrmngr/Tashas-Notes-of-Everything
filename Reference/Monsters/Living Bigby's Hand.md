---
type: pc
race: "Construct"
class:
 - "Living Bigby's Hand"
subClass:
 - "CR 4"
cover: "Living Bigby's Hand.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/4
  - source/idrotf
---
###### Living Bigby's Hand
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Living Bigby's Hand.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 52 (5d10 + 25) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 10 | 20 | 1 | 10 | 1 |
| **Mod** | +8 | +0 | +5 | -5 | +0 | -5 |

**Speed:** 0 ft., fly 60 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** —
**Saving Throws:** Dex +2, Wis +2
**Skills:** Perception +2, Stealth +2
**Damage Immunities:** poison
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned; unconscious

---

### Traits

**Magic Resistance.** The living spell has advantage on saving throws against spells and other magical effects.

**Unusual Nature.** The living spell doesn't require air, food, drink, or sleep.


---

### Actions

**Force Fist.** Melee Spell Attack: +10 to hit, reach 5 ft., one target. *Hit:* 26 (4d8 + 8) force damage. If the target is a Large or smaller creature, the living spell can move it up to 5 feet and move with it, without provoking opportunity attacks.

**Grasping Hand.** The living spell attempts to grab a Huge or smaller creature within 5 feet of it. The target must succeed on a DC 15 Dexterity saving throw or be grappled (escape DC 15). Until the grapple ends, the target takes 15 (2d6 + 8) bludgeoning damage at the start of each of its turns. The living spell can grapple only one creature at a time and can't use Force Fist until the grapple ends.


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
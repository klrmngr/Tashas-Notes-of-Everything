---
type: pc
race: "Celestial"
class:
 - "Equinal Guardinal"
subClass:
 - "CR 6"
cover: "Equinal Guardinal.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/large
  - cr/6
  - source/mpp
---
###### Equinal Guardinal
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Equinal Guardinal.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Celestial |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 93 (11d10 + 33) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 16 | 17 | 15 | 14 | 12 |
| **Mod** | +6 | +3 | +3 | +2 | +2 | +1 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Celestial, Common
**Saving Throws:** Str +9, Con +6
**Skills:** Athletics +9, Perception +5, Religion +5
**Damage Resistances:** radiant
**Condition Immunities:** charmed; frightened

---

### Traits

**Headfirst Charge.** If the equinal moves at least 30 feet in a straight line toward a creature and ends within 5 feet of it, that creature must succeed on a DC 17 Strength saving throw or take 14 (4d6) bludgeoning damage and have the prone condition.


---

### Actions

**Multiattack.** The equinal makes two Fist attacks.

**Fist.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 13 (2d6 + 6) bludgeoning damage plus 3 (1d6) radiant damage.

**Rock.** Ranged Weapon Attack: +9 to hit, range 60/180 ft., one target. *Hit:* 22 (3d10 + 6) bludgeoning damage. If the target is a creature, it must succeed on a DC 17 Strength saving throw or have the prone condition.

**Shout (Recharge 6).** The equinal lets out a booming shout. Each creature within 30 feet of the equinal must succeed on a DC 14 Constitution saving throw or have the stunned condition until the end of the equinal's next turn.


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
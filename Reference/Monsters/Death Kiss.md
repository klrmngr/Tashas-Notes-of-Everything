---
type: pc
race: "Aberration (beholder)"
class:
 - "Death Kiss"
subClass:
 - "CR 10"
cover: "Death Kiss.png"
campaign:
locations:
tags:
  - race/beholder
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/10
  - source/mpmm
---
###### Death Kiss
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Death Kiss.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Large Aberration (beholder) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 142 (15d10 + 60) |
> | :FasUserGroup: Race | Aberration (beholder) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 18 | 10 | 12 | 10 |
| **Mod** | +4 | +2 | +4 | +0 | +1 | +0 |

**Speed:** 0 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** Deep Speech, Undercommon
**Saving Throws:** Con +8, Wis +5
**Skills:** Perception +5
**Damage Immunities:** lightning
**Condition Immunities:** prone

---

### Traits

**Lightning Blood.** A creature within 5 feet of the death kiss takes 5 (1d10) lightning damage whenever it hits the death kiss with a melee attack that deals piercing or slashing damage.


---

### Actions

**Multiattack.** The death kiss makes three Tentacle attacks. Up to three of these attacks can be replaced by Blood Drain—one replacement per tentacle grappling a creature.

**Tentacle.** Melee Weapon Attack: +8 to hit, reach 20 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage, and the target is grappled (escape DC 14) if it is a Huge or smaller creature. Until this grapple ends, the target is restrained, and the death kiss can't use the same tentacle on another target. The death kiss has ten tentacles.

**Blood Drain.** One creature grappled by a tentacle of the death kiss must make a DC 16 Constitution saving throw. On a failed save, the target takes 22 (4d10) lightning damage, and the death kiss regains half as many hit points.


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
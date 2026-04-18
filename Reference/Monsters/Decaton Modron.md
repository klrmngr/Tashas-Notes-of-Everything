---
type: pc
race: "Construct"
class:
 - "Decaton Modron"
subClass:
 - "CR 8"
cover: "Decaton Modron.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/8
  - source/mpp
---
###### Decaton Modron
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Decaton Modron.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 144 (17d10 + 51) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 12 | 16 | 15 | 15 | 11 |
| **Mod** | +4 | +1 | +3 | +2 | +2 | +0 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 18
**Languages:** Modron, telepathy 120 ft.
**Saving Throws:** Int +5, Wis +5
**Skills:** Perception +8
**Condition Immunities:** charmed; frightened

---

### Traits

**Axiomatic Mind.** The decaton can't be compelled to act in a manner contrary to its nature or its instructions.

**Combat Ready.** The decaton has advantage on initiative rolls.

**Disintegration.** If the decaton dies, its body disintegrates into dust, leaving behind anything it was carrying.


---

### Actions

**Multiattack.** The decaton makes three Tentacle attacks.

**Tentacle.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 15 (2d10 + 4) piercing damage, and if the target is a Medium or smaller creature, it has the grappled condition (escape DC 14). Until this grapple ends, the decaton can't use this tentacle against other targets. The decaton has ten tentacles, each of which can grapple one target.

**Lightning Rays (Recharge 6).** The decaton unleashes a barrage of lightning bolts from its eyes. Each creature within 30 feet of the decaton must make a DC 13 Dexterity saving throw, taking 38 (7d10) lightning damage on a failed save, or half as much damage on a successful save.


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
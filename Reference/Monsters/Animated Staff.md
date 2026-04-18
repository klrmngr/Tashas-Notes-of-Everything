---
type: pc
race: "Construct"
class:
 - "Animated Staff"
subClass:
 - "CR —"
cover: "Animated Staff.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/—
  - source/wdmm
---
###### Animated Staff
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDMM
___

> [!infobox|no-t right]
> ![[Animated Staff.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 40 |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | WDMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 12 | 10 | 18 | 14 | 10 |
| **Mod** | +1 | +1 | +0 | +4 | +2 | +0 |

**Speed:** 0 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 12
**Languages:** Common
**Damage Resistances:** cold
**Damage Immunities:** poison

---

### Traits

**Wielder Domination.** A creature can grab the staff out of the air with a successful grapple check against the staff, and grappling the staff does not reduce the creature's speed. Any creature that successfully grapples the staff must succeed on a DC 12 Charisma saving throw or be charmed by the staff until the staff is no longer in its grasp. While the creature is charmed, the staff can issue commands to it, which the creature does its best to obey. The creature can repeat the saving throw each time it takes damage, ending the effect on itself on a success. A creature that successfully resists the staff's control can't be charmed by it for 24 hours.
A creature holding the staff that isn't charmed by it can use an action to attempt to break the staff over a knee or against a solid surface, doing so with a successful DC 17 Strength (Athletics) check. Breaking the staff in this manner destroys it.


---

### Actions

**Staff of Frost.** The staff has 10 charges. It can expend 1 or more of its charges to cast one of the following spells (save DC 12): cone of cold (5 charges), fog cloud (1 charge), ice storm (4 charges), or wall of ice (4 charges). It regains 1d6 + 4 expended charges daily at dawn. If the staff expends its last charge, roll a d20. On a 1, the staff turns to water and is destroyed.

**Staff.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (2d6) bludgeoning damage plus 1 cold damage.


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
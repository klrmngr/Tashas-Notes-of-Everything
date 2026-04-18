---
type: pc
race: "Plant"
class:
 - "Thorn Slinger"
subClass:
 - "CR 1/2"
cover: "Thorn Slinger.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/large
  - cr/1-2
  - source/tftyp
---
###### Thorn Slinger
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tales from the Yawning Portal
___

> [!infobox|no-t right]
> ![[Thorn Slinger.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Large Plant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 32 (5d10 + 5) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | Tales from the Yawning Portal |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 12 | 12 | 1 | 10 | 1 |
| **Mod** | +1 | +1 | +1 | -5 | +0 | -5 |

**Speed:** 10 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 10
**Languages:** —
**Condition Immunities:** blinded; deafened; frightened

---

### Traits

**Adhesive Blossoms.** The thorn slinger adheres to anything that touches it. A Medium or smaller creature adhered to the thorn slinger is also grappled by it (escape DC 11). Ability checks made to escape this grapple have disadvantage.
At the end of each of the thorn slinger's turns, anything grappled by it takes 3 (1d6) acid damage.

**False Appearance.** While the thorn slinger remains motionless, it is indistinguishable from an inanimate bush.


---

### Actions

**Thorns.** Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 30 ft., one target. *Hit:* 8 (2d6 + 1) piercing damage.


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
---
type: pc
race: "Aberration"
class:
 - "Cloaker"
subClass:
 - "CR 8"
cover: "Cloaker.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/8
  - source/xmm
---
###### Cloaker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Cloaker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 91 (14d10 + 14) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 15 | 12 | 13 | 14 | 7 |
| **Mod** | +3 | +2 | +1 | +1 | +2 | -2 |

**Speed:** 10 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 12
**Languages:** Deep Speech, Undercommon
**Skills:** Stealth +5
**Condition Immunities:** frightened

---

### Traits

**Light Sensitivity.** While in Bright Light, the cloaker has Disadvantage on attack rolls.


---

### Actions

**Multiattack.** The cloaker makes one Attach attack and two Tail attacks.

**Attach.** m +6, reach 5 ft. *Hit:* 13 (3d6 + 3) Piercing damage. If the target is a Large or smaller creature, the cloaker attaches to it. While the cloaker is attached, the target has the Blinded condition, and the cloaker can't make Attach attacks against other targets. In addition, the cloaker halves the damage it takes (round down), and the target takes the same amount of damage.
The cloaker can detach itself by spending 5 feet of movement. The target or a creature within 5 feet of it can take an action to try to detach the cloaker, doing so by succeeding on a DC 14 Strength (Athletics) check.

**Tail.** m +6, reach 10 ft. *Hit:* 8 (1d10 + 3) Slashing damage.


---

### Bonus Actions

**Moan.** wis DC 13, each creature in a 60-foot Emanation originating from the cloaker.  The target has the Frightened condition until the end of the cloaker's next turn.  The target is immune to this cloaker's Moan for the next 24 hours.


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
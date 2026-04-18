---
type: pc
race: "Aberration"
class:
 - "Grell"
subClass:
 - "CR 3"
cover: "Grell.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/3
  - source/xmm
---
###### Grell
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Grell.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 55 (10d8 + 10) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 14 | 13 | 12 | 11 | 9 |
| **Mod** | +2 | +2 | +1 | +1 | +0 | -1 |

**Speed:** 10 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., passive Perception 14
**Languages:** Deep Speech
**Skills:** Perception +4, Stealth +6
**Damage Immunities:** lightning
**Condition Immunities:** blinded; prone

---

### Traits

**Abduct.** The grell needn't spend extra movement to move a creature it is grappling.


---

### Actions

**Multiattack.** The grell makes one Beak attack and one Paralyzing Tentacles attack.

**Beak.** m +4, reach 5 ft. *Hit:* 11 (2d8 + 2) Piercing damage.

**Paralyzing Tentacles.** m +4, reach 10 ft. *Hit:* 7 (1d10 + 2) Piercing damage. If the target is a Medium or smaller creature, it has the Grappled condition (escape DC 12) from two of ten tentacles. The target is also subjected to the following effect. con DC 11.  The target has the Poisoned condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically. While Poisoned, the target has the Paralyzed condition.


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
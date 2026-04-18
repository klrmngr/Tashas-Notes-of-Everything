---
type: pc
race: "Elemental"
class:
 - "Ice Mephit"
subClass:
 - "CR 1/2"
cover: "Ice Mephit.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/small
  - cr/1-2
  - source/xmm
---
###### Ice Mephit
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Ice Mephit.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Small Elemental |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 21 (6d6) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 7 | 13 | 10 | 9 | 11 | 12 |
| **Mod** | -2 | +1 | +0 | -1 | +0 | +1 |

**Speed:** 30 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 12
**Languages:** Primordial (Aquan, Auran)
**Skills:** Perception +2, Stealth +3
**Damage Vulnerabilities:** fire
**Damage Immunities:** cold; poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Death Burst.** The mephit explodes when it dies. con DC 10, each creature in a 5-foot Emanation originating from the mephit.  5 (2d4) Cold damage.  Half damage.


---

### Actions

**Claw.** m +3, reach 5 ft. *Hit:* 3 (1d4 + 1) Slashing damage plus 2 (1d4) Cold damage.

**Frost Breath (Recharge 6).** con DC 10, each creature in a 15-foot Cone.  7 (3d4) Cold damage.  Half damage.


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
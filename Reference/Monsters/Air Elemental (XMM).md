---
type: pc
race: "Elemental"
class:
 - "Air Elemental"
subClass:
 - "CR 5"
cover: "Air Elemental.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/5
  - source/xmm
---
###### Air Elemental
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Air Elemental.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Elemental |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 90 (12d10 + 24) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 20 | 14 | 6 | 10 | 6 |
| **Mod** | +2 | +5 | +2 | -2 | +0 | -2 |

**Speed:** 10 ft., fly 90 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** Primordial (Auran)
**Damage Resistances:** bludgeoning; lightning; piercing; slashing
**Damage Immunities:** poison; thunder
**Condition Immunities:** exhaustion; grappled; paralyzed; petrified; poisoned; prone; restrained; unconscious

---

### Traits

**Air Form.** The elemental can enter a creature's space and stop there. It can move through a space as narrow as 1 inch without expending extra movement to do so.


---

### Actions

**Multiattack.** The elemental makes two Thunderous Slam attacks.

**Thunderous Slam.** m +8, reach 10 ft. *Hit:* 14 (2d8 + 5) Thunder damage.

**Whirlwind (Recharge 4–6).** str DC 13, one Medium or smaller creature in the elemental's space.  24 (4d10 + 2) Thunder damage, and the target is pushed up to 20 feet straight away from the elemental and has the Prone condition.  Half damage only.


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
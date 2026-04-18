---
type: pc
race: "Monstrosity"
class:
 - "Winter Wolf"
subClass:
 - "CR 3"
cover: "Winter Wolf.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/3
  - source/xmm
---
###### Winter Wolf
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Winter Wolf.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 75 (10d10 + 20) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 13 | 14 | 7 | 12 | 8 |
| **Mod** | +4 | +1 | +2 | -2 | +1 | -1 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common, Giant
**Skills:** Perception +5, Stealth +5
**Damage Immunities:** cold

---

### Traits

**Pack Tactics.** The wolf has Advantage on an attack roll against a creature if at least one of the wolf's allies is within 5 feet of the creature and the ally doesn't have the Incapacitated condition.


---

### Actions

**Bite.** m +6, reach 5 ft. *Hit:* 11 (2d6 + 4) Piercing damage. If the target is a Large or smaller creature, it has the Prone condition.

**Cold Breath (Recharge 5–6).** con DC 12, each creature in a 15-foot Cone.  18 (4d8) Cold damage.  Half damage.


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
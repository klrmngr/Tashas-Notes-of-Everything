---
type: pc
race: "Construct"
class:
 - "Gorgon"
subClass:
 - "CR 5"
cover: "Gorgon.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/5
  - source/xmm
---
###### Gorgon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Gorgon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 19 |
> | :FasHeart: HP | 114 (12d10 + 48) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 11 | 18 | 2 | 12 | 7 |
| **Mod** | +5 | +0 | +4 | -4 | +1 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 17
**Languages:** —
**Skills:** Perception +7
**Condition Immunities:** exhaustion; petrified

---

### Actions

**Gore.** m +8, reach 5 ft. *Hit:* 18 (2d12 + 5) Piercing damage. If the target is a Large or smaller creature and the gorgon moved 20+ feet straight toward it immediately before the hit, the target has the Prone condition.

**Petrifying Breath (Recharge 5–6).** con DC 15, each creature in a 30-foot Cone. 1 The target has the Restrained condition and repeats the save at the end of its next turn if it is still Restrained, ending the effect on itself on a success. 2 The target has the Petrified condition instead of the Restrained condition.


---

### Bonus Actions

**Trample.** dex DC 16, one creature within 5 feet that has the Prone condition.  16 (2d10 + 5) Bludgeoning damage.  Half damage.


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
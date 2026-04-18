---
type: pc
race: "Monstrosity"
class:
 - "Ankheg"
subClass:
 - "CR 2"
cover: "Ankheg.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/2
  - source/xmm
---
###### Ankheg
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Ankheg.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 45 (6d10 + 12) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 11 | 14 | 1 | 13 | 6 |
| **Mod** | +3 | +0 | +2 | -5 | +1 | -2 |

**Speed:** 30 ft., burrow 10 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., Tremorsense 60 ft., passive Perception 11
**Languages:** —

---

### Traits

**Tunneler.** The ankheg can burrow through solid rock at half its Burrow Speed and leaves a 10-foot-diameter tunnel in its wake.


---

### Actions

**Bite.** m +5 (with Advantage if the target is Grappled by the ankheg), reach 5 ft. *Hit:* 10 (2d6 + 3) Slashing damage plus 3 (1d6) Acid damage. If the target is a Large or smaller creature, it has the Grappled condition (escape DC 13).

**Acid Spray (Recharge 6).** dex DC 12, each creature in a 30-foot-long, 5-foot-wide Line.  14 (4d6) Acid damage.  Half damage.


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
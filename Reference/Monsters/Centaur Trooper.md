---
type: pc
race: "Fey"
class:
 - "Centaur Trooper"
subClass:
 - "CR 2"
cover: "Centaur Trooper.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/large
  - cr/2
  - source/xmm
---
###### Centaur Trooper
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Centaur Trooper.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Fey |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 45 (6d10 + 12) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 14 | 9 | 13 | 11 |
| **Mod** | +4 | +2 | +2 | -1 | +1 | +0 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Elvish, Sylvan
**Skills:** Athletics +6, Perception +3

---

### Actions

**Multiattack.** The centaur makes two attacks, using Pike or Longbow in any combination.

**Pike.** m +6, reach 10 ft. *Hit:* 9 (1d10 + 4) Piercing damage.

**Longbow.** r +4, range 150/600 ft. *Hit:* 6 (1d8 + 2) Piercing damage.


---

### Bonus Actions

**Trampling Charge (Recharge 5–6).** The centaur moves up to its Speed without provoking Opportunity Attacks and can move through the spaces of Medium or smaller creatures. Each creature whose space the centaur enters is targeted once by the following effect. str DC 14.  7 (1d6 + 4) Bludgeoning damage, and the target has the Prone condition.


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
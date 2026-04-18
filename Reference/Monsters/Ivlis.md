---
type: pc
race: "Humanoid (human)"
class:
 - "Ivlis"
subClass:
 - "CR 2"
cover: "Ivlis.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/hotb
---
###### Ivlis
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: HotB
___

> [!infobox|no-t right]
> ![[Ivlis.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 49 (10d8 + 10) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | HotB |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 14 | 12 | 10 | 14 | 14 |
| **Mod** | +0 | +2 | +1 | +0 | +2 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common
**Skills:** Deception +4, Persuasion +4

---

### Actions

**Multiattack.** Ivlis makes three Chaos Blast attacks. She can replace one attack with a use of Sinister Command if available.

**Chaos Blast.** m,r +4, reach 5 ft. or range 60 ft. *Hit:* 7 (2d6) damage. Roll 1d4 to determine the damage type: 1, Acid; 2, Cold; 3, Fire; 4, Lightning.

**Sinister Command (Recharge 5–6).** wis DC 12, one creature Ivlis can see within 60 feet.  The target has the Charmed condition until the end of its next turn. While Charmed, the target has the Incapacitated condition.


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
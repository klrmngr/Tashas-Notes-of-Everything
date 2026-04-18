---
type: pc
race: "Giant"
class:
 - "Fomorian"
subClass:
 - "CR 8"
cover: "Fomorian.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/8
  - source/xmm
---
###### Fomorian
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Fomorian.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 172 (15d12 + 75) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 10 | 20 | 9 | 14 | 6 |
| **Mod** | +6 | +0 | +5 | -1 | +2 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 18
**Languages:** Giant, Undercommon
**Skills:** Perception +8, Stealth +3

---

### Actions

**Multiattack.** The fomorian makes two Stone Club attacks. It can replace one attack with a use of Warping Hex if available.

**Stone Club.** m +9, reach 15 ft. *Hit:* 24 (4d8 + 6) Bludgeoning damage.

**Warping Hex (Recharge 4–6).** wis DC 16, one creature the fomorian can see within 120 feet.  21 (6d6) Psychic damage, and the target gains 1 Exhaustion level.  Half damage only.


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
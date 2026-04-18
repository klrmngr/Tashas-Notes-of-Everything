---
type: pc
race: "Beast"
class:
 - "Lion"
subClass:
 - "CR 1"
cover: "Lion.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/large
  - cr/1
  - source/xmm
---
###### Lion
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Lion.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Large Beast |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 22 (4d10) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 15 | 11 | 3 | 12 | 8 |
| **Mod** | +3 | +2 | +0 | -4 | +1 | -1 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 13
**Languages:** —
**Skills:** Perception +3, Stealth +4

---

### Traits

**Pack Tactics.** The lion has Advantage on an attack roll against a creature if at least one of the lion's allies is within 5 feet of the creature and the ally doesn't have the Incapacitated condition.

**Running Leap.** With a 10-foot running start, the lion can Long Jump up to 25 feet.


---

### Actions

**Multiattack.** The lion makes two Rend attacks. It can replace one attack with a use of Roar.

**Rend.** m +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Slashing damage.

**Roar.** wis DC 11, one creature within 15 feet.  The target has the Frightened condition until the start of the lion's next turn.


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
---
type: pc
race: "Monstrosity"
class:
 - "Bulette"
subClass:
 - "CR 5"
cover: "Bulette.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/5
  - source/xmm
---
###### Bulette
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Bulette.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 94 (9d10 + 45) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 11 | 21 | 2 | 10 | 5 |
| **Mod** | +4 | +0 | +5 | -4 | +0 | -3 |

**Speed:** 40 ft., burrow 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., Tremorsense 120 ft., passive Perception 16
**Languages:** —
**Skills:** Perception +6

---

### Actions

**Multiattack.** The bulette makes two Bite attacks.

**Bite.** m +7, reach 5 ft. *Hit:* 17 (2d12 + 4) Piercing damage.

**Deadly Leap.** The bulette spends 5 feet of movement to jump to a space within 15 feet that contains one or more Large or smaller creatures. dex DC 15, each creature in the bulette's destination space.  19 (3d12) Bludgeoning damage, and the target has the Prone condition.  Half damage, and the target is pushed 5 feet straight away from the bulette.


---

### Bonus Actions

**Leap.** The bulette jumps up to 30 feet by spending 10 feet of movement.


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
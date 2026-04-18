---
type: pc
race: "Beast"
class:
 - "Giant Ape"
subClass:
 - "CR 7"
cover: "Giant Ape.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/huge
  - cr/7
  - source/xmm
---
###### Giant Ape
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Giant Ape.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Huge Beast |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 168 (16d12 + 64) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 14 | 18 | 5 | 12 | 7 |
| **Mod** | +6 | +2 | +4 | -3 | +1 | -2 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** —
**Skills:** Athletics +9, Perception +4, Survival +4

---

### Actions

**Multiattack.** The ape makes two Fist attacks.

**Fist.** m +9, reach 10 ft. *Hit:* 22 (3d10 + 6) Bludgeoning damage.

**Boulder Toss (Recharge 6).** The ape hurls a boulder at a point it can see within 90 feet. dex DC 17, each creature in a 5-foot-radius Sphere centered on that point.  24 (7d6) Bludgeoning damage. If the target is a Large or smaller creature, it has the Prone condition.  Half damage only.


---

### Bonus Actions

**Leap.** The ape jumps up to 30 feet by spending 10 feet of movement.


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
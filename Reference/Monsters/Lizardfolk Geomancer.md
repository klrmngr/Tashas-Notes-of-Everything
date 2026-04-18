---
type: pc
race: "Elemental"
class:
 - "Lizardfolk Geomancer"
subClass:
 - "CR 2"
cover: "Lizardfolk Geomancer.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/medium
  - cr/2
  - source/xmm
---
###### Lizardfolk Geomancer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Lizardfolk Geomancer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Elemental |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 10 | 13 | 10 | 15 | 8 |
| **Mod** | +2 | +0 | +1 | +0 | +2 | -1 |

**Speed:** 30 ft., burrow 20 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Draconic, Primordial (Terran)
**Skills:** Nature +2, Perception +4, Stealth +4

---

### Actions

**Multiattack.** The lizardfolk makes two Earth Burst attacks.

**Earth Burst.** m,r +4, reach 5 ft. or range 60 ft. *Hit:* 9 (2d6 + 2) Bludgeoning damage.

**Hail of Stone (Recharge 5–6).** con DC 12, each creature in a 20-foot-radius, 40-foot-high Cylinder centered on a point the lizardfolk can see within 60 feet.  15 (6d4) Bludgeoning damage, and the target has the Prone condition.  Half damage only.


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
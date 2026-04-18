---
type: pc
race: "Elemental"
class:
 - "Merfolk Wavebender"
subClass:
 - "CR 6"
cover: "Merfolk Wavebender.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/medium
  - cr/6
  - source/xmm
---
###### Merfolk Wavebender
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Merfolk Wavebender.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Elemental |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 97 (15d8 + 30) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 18 | 14 | 13 | 19 | 15 |
| **Mod** | +0 | +4 | +2 | +1 | +4 | +2 |

**Speed:** 10 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 17
**Languages:** Common, Primordial (Aquan)
**Saving Throws:** Dex +7, Con +5, Wis +7, Cha +5
**Skills:** Perception +7
**Damage Resistances:** cold

---

### Traits

**Amphibious.** The merfolk can breathe air and water.


---

### Actions

**Multiattack.** The merfolk makes two Aquatic Burst attacks.

**Aquatic Burst.** m,r +7, reach 5 ft. or range 60 ft. *Hit:* 20 (3d10 + 4) Cold damage. If the target is a Large or smaller creature, it has the Prone condition.


---

### Reactions

**Watery Rebuke.**  An enemy the merfolk can see enters a space within 5 feet of the merfolk. dstr DC 15, the triggering enemy.  14 (4d6) Cold damage. If the target is Large or smaller, it is pushed up to 30 feet straight away from the merfolk by conjured water.


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
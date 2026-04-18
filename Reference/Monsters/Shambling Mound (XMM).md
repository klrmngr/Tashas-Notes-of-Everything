---
type: pc
race: "Plant"
class:
 - "Shambling Mound"
subClass:
 - "CR 5"
cover: "Shambling Mound.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/large
  - cr/5
  - source/xmm
---
###### Shambling Mound
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Shambling Mound.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Plant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 110 (13d10 + 39) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 8 | 16 | 5 | 10 | 5 |
| **Mod** | +4 | -1 | +3 | -3 | +0 | -3 |

**Speed:** 30 ft., swim 20 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., passive Perception 10
**Languages:** —
**Skills:** Stealth +3
**Damage Resistances:** cold; fire
**Damage Immunities:** lightning
**Condition Immunities:** deafened; exhaustion

---

### Traits

**Lightning Absorption.** Whenever the shambling mound is subjected to Lightning damage, it regains a number of Hit Points equal to the Lightning damage dealt.


---

### Actions

**Multiattack.** The shambling mound makes three Charged Tendril attacks. It can replace one attack with a use of Engulf.

**Charged Tendril.** m +7, reach 10 ft. *Hit:* 7 (1d6 + 4) Bludgeoning damage plus 5 (2d4) Lightning damage. If the target is a Medium or smaller creature, the shambling mound pulls the target 5 feet straight toward itself.

**Engulf.** str DC 15, one Medium or smaller creature within 5 feet.  The target is pulled into the shambling mound's space and has the Grappled condition (escape DC 14). Until the grapple ends, the target has the Blinded and Restrained conditions, and it takes 10 (3d6) Lightning damage at the start of each of its turns. When the shambling mound moves, the Grappled target moves with it, costing it no extra movement. The shambling mound can have only one creature Grappled by this action at a time.


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
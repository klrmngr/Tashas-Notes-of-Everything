---
type: pc
race: "Elemental"
class:
 - "Water Elemental"
subClass:
 - "CR 5"
cover: "Water Elemental.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/5
  - source/xmm
---
###### Water Elemental
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Water Elemental.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Elemental |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 114 (12d10 + 48) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 18 | 5 | 10 | 8 |
| **Mod** | +4 | +2 | +4 | -3 | +0 | -1 |

**Speed:** 30 ft., swim 90 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** Primordial (Aquan)
**Damage Resistances:** acid; fire
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; grappled; paralyzed; petrified; poisoned; prone; restrained; unconscious

---

### Traits

**Freeze.** If the elemental takes Cold damage, its Speed decreases by 20 feet until the end of its next turn.

**Water Form.** The elemental can enter an enemy's space and stop there. It can move through a space as narrow as 1 inch without expending extra movement to do so.


---

### Actions

**Multiattack.** The elemental makes two Slam attacks.

**Slam.** m +7, reach 5 ft. *Hit:* 13 (2d8 + 4) Bludgeoning damage. If the target is a Medium or smaller creature, it has the Prone condition.

**Whelm (Recharge 4–6).** str DC 15, each creature in the elemental's space.  22 (4d8 + 4) Bludgeoning damage. If the target is a Large or smaller creature, it has the Grappled condition (escape DC 14). Until the grapple ends, the target has the Restrained condition, is suffocating unless it can breathe water, and takes 9 (2d8) Bludgeoning damage at the start of each of the elemental's turns. The elemental can grapple one Large creature or up to two Medium or smaller creatures at a time with Whelm. As an action, a creature within 5 feet of the elemental can pull a creature out of it by succeeding on a DC 14 Strength (Athletics) check.  Half damage only.


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
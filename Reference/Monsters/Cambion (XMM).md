---
type: pc
race: "Fiend"
class:
 - "Cambion"
subClass:
 - "CR 5"
cover: "Cambion.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/5
  - source/xmm
---
###### Cambion
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Cambion.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 19 |
> | :FasHeart: HP | 105 (14d8 + 42) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 18 | 16 | 14 | 12 | 16 |
| **Mod** | +4 | +4 | +3 | +2 | +1 | +3 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 14
**Languages:** Abyssal, Common, Infernal
**Saving Throws:** Str +7, Con +6, Int +5, Cha +6
**Skills:** Deception +6, Perception +4, Stealth +7
**Damage Resistances:** cold; fire; lightning; poison
**Condition Immunities:** poisoned

---

### Actions

**Multiattack.** The cambion makes two attacks, using Claw or Fire Ray in any combination.

**Claw.** m +7, reach 5 ft. *Hit:* 8 (1d8 + 4) Slashing damage plus 7 (2d6) Fire damage.

**Fire Ray.** r +7, range 120 ft. *Hit:* 13 (3d6 + 3) Fire damage.


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
---
type: pc
race: "Undead"
class:
 - "Ghast"
subClass:
 - "CR 2"
cover: "Ghast.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/2
  - source/xmm
---
###### Ghast
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Ghast.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 36 (8d8) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 17 | 10 | 11 | 10 | 8 |
| **Mod** | +3 | +3 | +0 | +0 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** Common
**Saving Throws:** Wis +2
**Damage Resistances:** necrotic
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; poisoned

---

### Traits

**Stench.** con DC 10, any creature that starts its turn in a 5-foot Emanation originating from the ghast.  The target has the Poisoned condition until the start of its next turn.  The target is immune to this ghast's Stench for 24 hours.


---

### Actions

**Bite.** m +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Piercing damage plus 9 (2d8) Necrotic damage.

**Claw.** m +5, reach 5 ft. *Hit:* 10 (2d6 + 3) Slashing damage. If the target is a non-Undead creature, it is subjected to the following effect. con DC 10.  The target has the Paralyzed condition until the end of its next turn.


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
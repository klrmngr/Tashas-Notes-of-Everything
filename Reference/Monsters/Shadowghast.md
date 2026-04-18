---
type: pc
race: "Undead"
class:
 - "Shadowghast"
subClass:
 - "CR 5"
cover: "Shadowghast.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/5
  - source/egw
---
###### Shadowghast
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Explorer's Guide to Wildemount
___

> [!infobox|no-t right]
> ![[Shadowghast.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 49 (9d8 + 9) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Explorer's Guide to Wildemount |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 20 | 12 | 12 | 11 | 8 |
| **Mod** | +2 | +5 | +1 | +1 | +0 | -1 |

**Speed:** 35 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** —
**Skills:** Perception +3, Stealth +8
**Damage Resistances:** necrotic
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; poisoned

---

### Traits

**Stench.** Any creature that starts its turn within 5 feet of the shadowghast must succeed on a DC 12 Constitution saving throw or be poisoned until the start of its next turn. On a successful saving throw, the creature is immune to this Stench for 24 hours.

**Shadow Stealth.** While in dim light or darkness, the shadowghast can take the Hide action as a bonus action.


---

### Actions

**Multiattack.** The shadowghast makes two attacks: one with its bite and one with its claws.

**Bite.** Melee Weapon Attack: +8 to hit, reach 5 ft., one creature. *Hit:* 11 (2d8 + 2) slashing damage plus 5 (1d10) necrotic damage.

**Claws.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) slashing damage. If the target is a creature other than an undead, it must succeed on a DC 12 Constitution saving throw or be paralyzed for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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
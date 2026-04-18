---
type: pc
race: "Construct"
class:
 - "Dzaan's Simulacrum"
subClass:
 - "CR 1"
cover: "Dzaan's Simulacrum.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/1
  - source/idrotf
---
###### Dzaan's Simulacrum
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Dzaan's Simulacrum.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 24 (9d8 + 9) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 11 | 12 | 16 | 13 | 15 |
| **Mod** | +0 | +0 | +1 | +3 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Abyssal, Common, Giant, Infernal
**Saving Throws:** Int +5, Wis +3
**Skills:** Arcana +5, Deception +4, History +5

---

### Actions

**Shocking Grasp (Cantrip).** Melee Spell Attack: +5 to hit, reach 5 ft., one creature (the attack roll has advantage if the target is wearing armor made of metal). *Hit:* 9 (2d8) lightning damage, and the target can't take reactions until the start of its next turn.

**Acid Splash (Cantrip).** The simulacrum hurls a bubble of acid at one creature it can see within 60 feet of it, or at two such creatures that are within 5 feet of each other. A target must succeed on a DC 13 Dexterity saving throw or take 7 (2d6) acid damage.

**Magic Missile (1st-Level Spell; Requires a Spell Slot).** The simulacrum creates three darts of magical force. Each dart unerringly strikes one creature the simulacrum can see within 120 feet of it, dealing 3 (1d4 + 1) force damage. If the simulacrum casts this spell using a 2nd-level spell slot, it creates one more dart.


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
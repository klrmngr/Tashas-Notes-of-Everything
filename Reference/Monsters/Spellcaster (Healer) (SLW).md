---
type: pc
race: "Humanoid (healer)"
class:
 - "Spellcaster (Healer)"
subClass:
 - "CR —"
cover: "Spellcaster (Healer).png"
campaign:
locations:
tags:
  - race/healer
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/—
  - source/slw
---
###### Spellcaster (Healer)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: SLW
___

> [!infobox|no-t right]
> ![[Spellcaster (Healer).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid (healer) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 13 (studded leather) |
> | :FasHeart: HP | 36 (8d8) |
> | :FasUserGroup: Race | Humanoid (healer) |
> | :FasBook: Source | SLW |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 12 | 10 | 15 | 16 | 13 |
| **Mod** | +0 | +1 | +0 | +2 | +3 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, plus one of your choice
**Saving Throws:** Wis +6
**Skills:** Arcana +5, Investigation +5, Religion +5

---

### Traits

**Potent Cantrip.** The spellcaster can add its spellcasting ability modifier to the damage it deals with any cantrip.


---

### Actions

**Quarterstaff.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d6) bludgeoning damage, or 4 (1d8) bludgeoning damage if used with two hands.


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
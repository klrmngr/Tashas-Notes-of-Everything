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
  - source/sdw
---
###### Spellcaster (Healer)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: SDW
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
> | :FasHeart: HP | 45 (10d8) |
> | :FasUserGroup: Race | Humanoid (healer) |
> | :FasBook: Source | SDW |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 12 | 10 | 15 | 18 | 13 |
| **Mod** | +0 | +1 | +0 | +2 | +4 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Common, plus one of your choice
**Saving Throws:** Wis +8
**Skills:** Arcana +6, Investigation +6, Religion +6

---

### Traits

**Potent Cantrip.** The spellcaster can add its spellcasting ability modifier to the damage it deals with any cantrip.


---

### Actions

**Quarterstaff.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 3 (1d6) bludgeoning damage, or 4 (1d8) bludgeoning damage if used with two hands.


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
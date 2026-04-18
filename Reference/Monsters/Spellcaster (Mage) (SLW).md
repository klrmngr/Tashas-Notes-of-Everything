---
type: pc
race: "Humanoid (mage)"
class:
 - "Spellcaster (Mage)"
subClass:
 - "CR —"
cover: "Spellcaster (Mage).png"
campaign:
locations:
tags:
  - race/mage
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/—
  - source/slw
---
###### Spellcaster (Mage)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: SLW
___

> [!infobox|no-t right]
> ![[Spellcaster (Mage).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid (mage) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 13 (studded leather) |
> | :FasHeart: HP | 36 (8d8) |
> | :FasUserGroup: Race | Humanoid (mage) |
> | :FasBook: Source | SLW |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 12 | 10 | 16 | 14 | 13 |
| **Mod** | +0 | +1 | +0 | +3 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, plus one of your choice
**Saving Throws:** Wis +5
**Skills:** Arcana +6, Investigation +6, Religion +6

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
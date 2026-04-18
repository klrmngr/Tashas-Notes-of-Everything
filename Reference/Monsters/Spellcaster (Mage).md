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
  - source/dc
---
###### Spellcaster (Mage)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: DC
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
> | :FasHeart: HP | 54 (12d8) |
> | :FasUserGroup: Race | Humanoid (mage) |
> | :FasBook: Source | DC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 12 | 10 | 18 | 14 | 14 |
| **Mod** | +0 | +1 | +0 | +4 | +2 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, plus one of your choice
**Saving Throws:** Wis +6
**Skills:** Arcana +8, Investigation +8, Religion +8

---

### Traits

**Empowered Spells.** Whenever the spellcaster casts a spell of the evocation school by expending a spell slot, the spellcaster can add its spellcasting ability modifier to the spell's damage roll or healing roll, if any.

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
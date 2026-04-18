---
type: pc
race: "Humanoid (human, wizard)"
class:
 - "Manshoon"
subClass:
 - "CR 13"
cover: "Manshoon.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/13
  - source/fraif
---
###### Manshoon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Manshoon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human, wizard) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 214 (33d8 + 66) |
> | :FasUserGroup: Race | Humanoid (human, wizard) |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 14 | 23 | 15 | 16 |
| **Mod** | +0 | +2 | +2 | +6 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 12
**Languages:** Common, Draconic, Infernal, Undercommon
**Saving Throws:** Int +11, Wis +7
**Skills:** Arcana +11, History +11, Insight +7
**Damage Immunities:** psychic
**Condition Immunities:** charmed

---

### Traits

**Magic Resistance.** Manshoon has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Manshoon makes three Arcane Burst attacks. He can replace two attacks with a use of Spellcasting.

**Arcane Burst.** m,r +11, reach 5 ft., or range 120 ft. *Hit:* 32 (4d12 + 6) Force damage.


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
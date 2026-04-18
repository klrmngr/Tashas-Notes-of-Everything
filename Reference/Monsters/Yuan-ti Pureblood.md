---
type: pc
race: "Humanoid (yuan-ti)"
class:
 - "Yuan-ti Pureblood"
subClass:
 - "CR 1"
cover: "Yuan-ti Pureblood.png"
campaign:
locations:
tags:
  - race/yuan-ti
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/mm
---
###### Yuan-ti Pureblood
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Yuan-ti Pureblood.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (yuan-ti) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 40 (9d8) |
> | :FasUserGroup: Race | Humanoid (yuan-ti) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 12 | 11 | 13 | 12 | 14 |
| **Mod** | +0 | +1 | +0 | +1 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Abyssal, Common, Draconic
**Skills:** Deception +6, Perception +3, Stealth +3
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Magic Resistance.** The yuan-ti has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The yuan-ti makes two melee attacks.

**Scimitar.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 4 (1d6 + 1) slashing damage.

**Shortbow.** Ranged Weapon Attack: +3 to hit, range 80/320 ft., one target. *Hit:* 4 (1d6 + 1) piercing damage plus 7 (2d6) poison damage.


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
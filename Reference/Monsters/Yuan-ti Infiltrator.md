---
type: pc
race: "Monstrosity"
class:
 - "Yuan-ti Infiltrator"
subClass:
 - "CR 1"
cover: "Yuan-ti Infiltrator.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/1
  - source/xmm
---
###### Yuan-ti Infiltrator
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Yuan-ti Infiltrator.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 40 (9d8) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 12 | 11 | 13 | 14 | 12 |
| **Mod** | +0 | +1 | +0 | +1 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 14
**Languages:** Abyssal, Common, Draconic
**Skills:** Deception +5, Perception +4, Stealth +3
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Magic Resistance.** The yuan-ti has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The yuan-ti makes two Scimitar attacks.

**Scimitar.** m +3, reach 5 ft. *Hit:* 4 (1d6 + 1) Slashing damage.

**Poison Ray.** r +4, range 120 ft. *Hit:* 9 (2d6 + 2) Poison damage.


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
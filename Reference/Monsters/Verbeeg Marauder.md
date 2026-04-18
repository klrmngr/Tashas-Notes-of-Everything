---
type: pc
race: "Giant"
class:
 - "Verbeeg Marauder"
subClass:
 - "CR 4"
cover: "Verbeeg Marauder.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/large
  - cr/4
  - source/idrotf
---
###### Verbeeg Marauder
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Verbeeg Marauder.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Giant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 (hide armor, shield) |
> | :FasHeart: HP | 85 (10d10 + 30) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 11 | 16 | 11 | 10 | 9 |
| **Mod** | +4 | +0 | +3 | +0 | +0 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common, Giant
**Saving Throws:** Dex +2, Con +5
**Skills:** Animal Handling +2, Athletics +6, Stealth +2

---

### Traits

**Simple Weapon Wielder.** A simple weapon deals one extra die of its damage when the verbeeg hits with it (included in the attack).


---

### Actions

**Multiattack.** The verbeeg makes two melee attacks.

**Spear.** Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 14 (3d6 + 4) piercing damage, or 17 (3d8 + 4) piercing damage if used to make a ranged attack or used with two hands to make a melee attack.


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
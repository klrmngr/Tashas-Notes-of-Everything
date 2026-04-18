---
type: pc
race: "Fey"
class:
 - "Siren"
subClass:
 - "CR 3"
cover: "Siren.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/3
  - source/tftyp
---
###### Siren
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tales from the Yawning Portal
___

> [!infobox|no-t right]
> ![[Siren.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 38 (7d8 + 7) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | Tales from the Yawning Portal |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 18 | 12 | 13 | 14 | 16 |
| **Mod** | +0 | +4 | +1 | +1 | +2 | +3 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Common, Elvish, Sylvan
**Skills:** Medicine +4, Nature +3, Stealth +6, Survival +4

---

### Traits

**Amphibious.** Siren can breathe air and water.

**Magic Resistance.** Siren has advantage on saving throws against spells and other magical effects.


---

### Actions

**Shortsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage.

**Stupefying Touch.** Siren touches one creature she can see within 5 feet of her. The creature must succeed on a DC 13 Intelligence saving throw or take 13 (3d6 + 3) psychic damage and be stunned until the start of Siren's next turn.


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
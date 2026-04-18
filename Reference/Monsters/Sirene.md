---
type: pc
race: "Fey"
class:
 - "Sirene"
subClass:
 - "CR 3"
cover: "Sirene.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/3
  - source/mabjov
---
###### Sirene
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Sirene.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 63 (14d8) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 18 | 11 | 12 | 10 | 16 |
| **Mod** | +1 | +4 | +0 | +1 | +0 | +3 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60ft., passive Perception 10
**Languages:** Common, Elvish, Sylvan
**Skills:** Performance +5, Persuasion +5, Stealth +6

---

### Traits

**Amphibious.** The sirene can breathe air and water.

**Magic Resistance.** The sirene has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The sirene makes two Dagger attacks or two Shortbow attacks.

**Dagger.** Melee Weapon Attack: +6 to hit, range 5 ft., one target. *Hit:* 6 (1d4 + 4) piercing damage plus 3 (1d6) cold damage.

**Shortbow.** Ranged Weapon Attack: +6 to hit, range 80/320 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage.

**Sirene's Song (2/Day).** The sirene casts suggestion with a range of 1 mile that affects all creatures of the sirene's choosing in range. Each target has disadvantage on the saving throw.


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
---
type: pc
race: "Fiend (demon, orc)"
class:
 - "Tanarukk"
subClass:
 - "CR 5"
cover: "Tanarukk.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/5
  - source/vgm
---
###### Tanarukk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Tanarukk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Fiend (demon, orc) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 95 (10d8 + 50) |
> | :FasUserGroup: Race | Fiend (demon, orc) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 13 | 20 | 9 | 9 | 9 |
| **Mod** | +4 | +1 | +5 | -1 | -1 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Abyssal, Common, Orc
**Skills:** Intimidation +2, Perception +2
**Damage Resistances:** fire; poison

---

### Traits

**Aggressive.** As a bonus action, the tanarukk can move up to its speed toward a hostile creature that it can see.

**Magic Resistance.** The tanarukk has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The tanarukk makes two attacks: one with its bite and one with its greatsword.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) piercing damage.

**Greatsword.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage.


---

### Reactions

**Unbridled Fury.** In response to being hit by a melee attack, the tanarukk can make one melee weapon attack with advantage against the attacker.


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
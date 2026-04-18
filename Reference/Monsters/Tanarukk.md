---
type: pc
race: "Fiend (demon)"
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
  - source/mpmm
---
###### Tanarukk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Tanarukk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Fiend (demon) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 95 (10d8 + 50) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 13 | 20 | 9 | 9 | 9 |
| **Mod** | +4 | +1 | +5 | -1 | -1 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Abyssal, Common, plus any one language
**Skills:** Intimidation +2, Perception +2
**Damage Resistances:** fire; poison

---

### Traits

**Magic Resistance.** The tanarukk has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The tanarukk makes one Bite attack and one Greatsword attack.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) piercing damage.

**Greatsword.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage.


---

### Bonus Actions

**Aggressive.** The tanarukk moves up to its speed toward an enemy that it can see.


---

### Reactions

**Unbridled Fury.** In response to being hit by a melee attack, the tanarukk can make one Bite or Greatsword attack with advantage against the attacker.


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
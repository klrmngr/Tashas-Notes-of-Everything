---
type: pc
race: "Monstrosity"
class:
 - "Yeti Tyke"
subClass:
 - "CR 1/8"
cover: "Yeti Tyke.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/small
  - cr/1-8
  - source/mgelft
---
###### Yeti Tyke
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MGELFT
___

> [!infobox|no-t right]
> ![[Yeti Tyke.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Small Monstrosity |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 11 (natural armor) |
> | :FasHeart: HP | 9 (2d6 + 2) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | MGELFT |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 11 | 12 | 6 | 8 | 5 |
| **Mod** | +0 | +0 | +1 | -2 | -1 | -3 |

**Speed:** 20 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 9
**Languages:** understands Yeti but can't speak
**Damage Immunities:** cold

---

### Traits

**Keen Smell.** The yeti tyke has advantage on Wisdom (Perception) checks that rely on smell.

**Snow Camouflage.** The yeti tyke has advantage on Dexterity (Stealth) checks made to hide in snowy terrain.


---

### Actions

**Claw.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 3 (1d4 + 1) slashing damage, plus 2 (1d4) cold damage. Claw does both slashing and cold damage.


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
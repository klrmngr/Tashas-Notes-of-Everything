---
type: pc
race: "Monstrosity"
class:
 - "Skyjek Roc"
subClass:
 - "CR 2"
cover: "Skyjek Roc.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/2
  - source/ggr
---
###### Skyjek Roc
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Skyjek Roc.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (breastplate) |
> | :FasHeart: HP | 37 (5d10 + 10) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 13 | 14 | 3 | 10 | 8 |
| **Mod** | +5 | +1 | +2 | -4 | +0 | -1 |

**Speed:** 20 ft., fly 90 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** —
**Saving Throws:** Dex +3, Wis +2
**Skills:** Perception +2

---

### Traits

**Keen Sight.** The roc has advantage on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** The roc makes two attacks: one with its beak and one with its talons.

**Beak.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 9 (1d8 + 5) piercing damage.

**Talons.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 10 (2d4 + 5) slashing damage.


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
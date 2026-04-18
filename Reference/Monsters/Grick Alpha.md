---
type: pc
race: "Monstrosity"
class:
 - "Grick Alpha"
subClass:
 - "CR 7"
cover: "Grick Alpha.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/7
  - source/mm
---
###### Grick Alpha
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Grick Alpha.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 75 (10d10 + 20) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 16 | 15 | 4 | 14 | 9 |
| **Mod** | +4 | +3 | +2 | -3 | +2 | -1 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** —
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks

---

### Traits

**Stone Camouflage.** The grick has advantage on Dexterity (Stealth) checks made to hide in rocky terrain.


---

### Actions

**Multiattack.** The grick makes two attacks: one with its tail and one with its tentacles. If it hits with its tentacles, the grick can make one beak attack against the same target.

**Tail.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 11 (2d6 + 4) bludgeoning damage.

**Tentacles.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 22 (4d8 + 4) slashing damage.

**Beak.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 13 (2d8 + 4) piercing damage.


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
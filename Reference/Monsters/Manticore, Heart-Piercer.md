---
type: pc
race: "Monstrosity"
class:
 - "Manticore, Heart-Piercer"
subClass:
 - "CR 5"
cover: "Manticore, Heart-Piercer.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/5
  - source/psa
---
###### Manticore, Heart-Piercer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: PSA
___

> [!infobox|no-t right]
> ![[Manticore, Heart-Piercer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 136 (16d10 + 48) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | PSA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 14 | 16 | 5 | 12 | 6 |
| **Mod** | +4 | +2 | +3 | -3 | +1 | -2 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** —
**Skills:** Perception +4

---

### Actions

**Multiattack.** The manticore makes two attacks, one with its bite and one with its claws.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage.

**Claws.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) slashing damage.

**Stinger.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage. The target must make a DC 14 Constitution saving throw, taking 24 (7d6) poison damage on a failed save, or half as much damage on a successful one.


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
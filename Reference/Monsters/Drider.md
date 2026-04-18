---
type: pc
race: "Monstrosity"
class:
 - "Drider"
subClass:
 - "CR 6"
cover: "Drider.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/6
  - source/mm
---
###### Drider
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Drider.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 123 (13d10 + 52) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 16 | 18 | 13 | 14 | 12 |
| **Mod** | +3 | +3 | +4 | +1 | +2 | +1 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** Elvish, Undercommon
**Skills:** Perception +5, Stealth +9

---

### Traits

**Fey Ancestry.** The drider has advantage on saving throws against being charmed, and magic can't put the drider to sleep.

**Spider Climb.** The drider can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Sunlight Sensitivity.** While in sunlight, the drider has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.

**Web Walker.** The drider ignores movement restrictions caused by webbing.


---

### Actions

**Multiattack.** The drider makes three attacks, either with its longsword or its longbow. It can replace one of those attacks with a bite attack.

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. *Hit:* 2 (1d4) piercing damage plus 9 (2d8) poison damage.

**Longsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands.

**Longbow.** Ranged Weapon Attack: +6 to hit, range 150/600 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage plus 4 (1d8) poison damage.


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
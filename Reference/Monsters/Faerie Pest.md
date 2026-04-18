---
type: pc
race: "Fey"
class:
 - "Faerie Pest"
subClass:
 - "CR 1"
cover: "Faerie Pest.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/small
  - cr/1
  - source/mcv4ec
---
###### Faerie Pest
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV4EC
___

> [!infobox|no-t right]
> ![[Faerie Pest.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Small Fey |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 (leather armor) |
> | :FasHeart: HP | 22 (5d6 + 5) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | MCV4EC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 16 | 12 | 10 | 12 | 14 |
| **Mod** | -1 | +3 | +1 | +0 | +1 | +2 |

**Speed:** 30 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Sylvan
**Skills:** Perception +3, Stealth +7

---

### Actions

**Stingblade.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage plus 5 (2d4) poison damage. If the faerie had advantage on the attack roll, the target takes an additional 3 (1d6) slashing damage.

**Theft of Nerves (1/Day).** The faerie unleashes a burst of mind-muddling magic in a 15-foot cone. Each creature in that area must succeed on a DC 12 Intelligence saving throw or have the frightened condition for 1 minute. A frightened creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


---

### Bonus Actions

**Mischievous Stealth.** The faerie takes the Hide action.


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
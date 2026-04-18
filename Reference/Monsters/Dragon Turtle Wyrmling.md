---
type: pc
race: "Dragon"
class:
 - "Dragon Turtle Wyrmling"
subClass:
 - "CR 4"
cover: "Dragon Turtle Wyrmling.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/4
  - source/ftd
---
###### Dragon Turtle Wyrmling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Dragon Turtle Wyrmling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Dragon |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 90 (12d10 + 24) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 10 | 15 | 8 | 10 | 10 |
| **Mod** | +3 | +0 | +2 | -1 | +0 | +0 |

**Speed:** 20 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 10
**Languages:** Draconic
**Saving Throws:** Dex +2, Con +4, Wis +2
**Damage Resistances:** fire

---

### Traits

**Amphibious.** The dragon turtle can breathe air and water.


---

### Actions

**Bite.** Melee Weapon Attack: +5 to hit, reach 10 ft., one target. *Hit:* 11 (1d12 + 3) piercing damage.

**Steam Breath (Recharge 5–6).** The dragon turtle exhales steam in a 15-foot cone. Each creature in that area must make a DC 12 Constitution saving throw, taking 17 (5d6) fire damage on a failed save, or half as much damage on a successful one. Being underwater doesn't grant resistance against this damage.


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
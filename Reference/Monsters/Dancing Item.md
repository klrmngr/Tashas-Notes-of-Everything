---
type: pc
race: "Construct"
class:
 - "Dancing Item"
subClass:
 - "CR —"
cover: "Dancing Item.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/—
  - source/tce
---
###### Dancing Item
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tasha's Cauldron of Everything
___

> [!infobox|no-t right]
> ![[Dancing Item.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 10 + five times your bard level |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Tasha's Cauldron of Everything |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 16 | 4 | 10 | 6 |
| **Mod** | +4 | +2 | +3 | -3 | +0 | -2 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** understands the languages you speak
**Damage Immunities:** poison; psychic
**Condition Immunities:** charmed; exhaustion; poisoned; frightened

---

### Traits

**Immutable Form.** The item is immune to any spell or effect that would alter its form.

**Irrepressible Dance.** When any creature starts its turn within 10 feet of the item, the item can increase or decrease (your choice) the walking speed of that creature by 10 feet until the end of the turn, provided the item isn't incapacitated.


---

### Actions

**Force-Empowered Slam.** Melee Weapon Attack:  to hit, reach 5 ft., one target you can see. *Hit:* 1d10 + PB force damage.


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
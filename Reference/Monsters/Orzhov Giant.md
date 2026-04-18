---
type: pc
race: "Giant"
class:
 - "Orzhov Giant"
subClass:
 - "CR 6"
cover: "Orzhov Giant.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/large
  - cr/6
  - source/ggr
---
###### Orzhov Giant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Orzhov Giant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Giant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 84 (8d10 + 40) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 13 | 21 | 12 | 13 | 8 |
| **Mod** | +6 | +1 | +5 | +1 | +1 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Common, Giant
**Saving Throws:** Dex +4, Con +8, Wis +4

---

### Traits

**Focus.** As a bonus action, the giant can target a creature it can see within 30 feet of it and make that creature its focus. The target remains the giant's focus for 1 minute, or until either the target or the giant drops to 0 hit points. When the giant makes an attack roll against its focus, it adds a d4 to its attack roll. If the giant attacks a different target while it has a focus, it subtracts a d4 from its attack roll.


---

### Actions

**Multiattack.** The giant makes two greataxe attacks.

**Greataxe.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 25 (3d12 + 6) slashing damage. If the Orzhov giant scores a critical hit, it rolls the damage dice three times, instead of twice.

**Rock.** Ranged Weapon Attack: +9 to hit, range 60/240 ft., one target. *Hit:* 28 (4d10 + 6) bludgeoning damage.


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
---
type: pc
race: "Humanoid (human)"
class:
 - "Meloon Wardragon"
subClass:
 - "CR 9"
cover: "Meloon Wardragon.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/wdh
---
###### Meloon Wardragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Meloon Wardragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 143 (22d8 + 44) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 15 | 14 | 10 | 14 | 15 |
| **Mod** | +5 | +2 | +2 | +0 | +2 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Common, Deep Speech, telepathy 60 ft.
**Saving Throws:** Str +9, Con +6
**Skills:** Athletics +9, Survival +6

---

### Traits

**Special Equipment.** Meloon wields Azuredge but can't attune to it, and thus gains none of its benefits.

**Indomitable (2/Day).** Meloon can reroll a saving throw that he fails. He must use the new roll.

**Second Wind (Recharges after a Short or Long Rest).** As a bonus action, Meloon can regain 20 hit points.


---

### Actions

**Multiattack.** Meloon makes four attacks with Azuredge.

**Azuredge.** m attack: +9 to hit, reach 5 ft., one target. *Hit:* 11 (1d12 + 5) slashing damage.


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
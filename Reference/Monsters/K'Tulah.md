---
type: pc
race: "Humanoid (tabaxi)"
class:
 - "K'Tulah"
subClass:
 - "CR 2"
cover: "K'Tulah.png"
campaign:
locations:
tags:
  - race/tabaxi
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/cm
---
###### K'Tulah
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Candlekeep Mysteries
___

> [!infobox|no-t right]
> ![[K'Tulah.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (tabaxi) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 27 (5d8 + 5) |
> | :FasUserGroup: Race | Humanoid (tabaxi) |
> | :FasBook: Source | Candlekeep Mysteries |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 12 | 13 | 12 | 15 | 11 |
| **Mod** | +0 | +1 | +1 | +1 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Common, Druidic
**Skills:** Medicine +4, Nature +3, Perception +4

---

### Traits

**Feline Agility.** When K'Tulah moves on her turn in combat, she can double her speed until the end of the turn. Once she uses this ability, K'Tulah can't use it again until she moves 0 feet on one of her turns.


---

### Actions

**Quarterstaff.** Melee Weapon Attack: +2 to hit (+4 to hit with shillelagh), reach 5 ft., one target. *Hit:* 3 (1d6) bludgeoning damage, 4 (1d8) bludgeoning damage if wielded with two hands, or 6 (1d8 + 2) bludgeoning damage with shillelagh.

**Claws.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 2 (1d4) slashing damage.


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
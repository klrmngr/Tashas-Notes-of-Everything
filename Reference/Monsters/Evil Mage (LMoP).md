---
type: pc
race: "Humanoid (human)"
class:
 - "Evil Mage"
subClass:
 - "CR 1"
cover: "Evil Mage.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/lmop
---
###### Evil Mage
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Lost Mine of Phandelver
___

> [!infobox|no-t right]
> ![[Evil Mage.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 22 (5d8) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Lost Mine of Phandelver |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 14 | 11 | 17 | 12 | 11 |
| **Mod** | -1 | +2 | +0 | +3 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common, Draconic, Dwarvish, Elvish
**Saving Throws:** Int +5, Wis +3
**Skills:** Arcana +5, History +5

---

### Actions

**Quarterstaff.** Melee Weapon Attack: +1 to hit, reach 5 ft., one target. *Hit:* 3 (1d8 - 1) bludgeoning damage.


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
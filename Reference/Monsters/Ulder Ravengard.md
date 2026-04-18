---
type: pc
race: "Humanoid (human)"
class:
 - "Ulder Ravengard"
subClass:
 - "CR 5"
cover: "Ulder Ravengard.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/bgdia
---
###### Ulder Ravengard
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGDIA
___

> [!infobox|no-t right]
> ![[Ulder Ravengard.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 20 (plate armor, shield) |
> | :FasHeart: HP | 112 (15d8 + 45) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | BGDIA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 14 | 16 | 11 | 10 | 17 |
| **Mod** | +3 | +2 | +3 | +0 | +0 | +3 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common
**Saving Throws:** Con +6, Wis +3
**Skills:** Athletics +6, Intimidation +6, Perception +3

---

### Actions

**Multiattack.** Ulder makes three melee attacks, only one of which can be with his shield.

**+1 Longsword.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage, or 9 (1d10 + 4) slashing damage when used with two hands.

**Shield.** Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. *Hit:* 6 (1d6 + 3) bludgeoning damage, and Ulder pushes the target 5 feet away from him. Ulder then enters the space vacated by the target. If the target is pushed to within 5 feet of a creature friendly to Ulder, the target provokes an opportunity attack from that creature.


---

### Reactions

**Guardian Strike.** If an enemy within 5 feet of Ulder attacks a target other than him, Ulder can make a melee attack against that enemy.


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
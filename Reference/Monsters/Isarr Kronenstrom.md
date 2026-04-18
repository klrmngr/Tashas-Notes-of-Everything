---
type: pc
race: "Humanoid (human)"
class:
 - "Isarr Kronenstrom"
subClass:
 - "CR 8"
cover: "Isarr Kronenstrom.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/8
  - source/idrotf
---
###### Isarr Kronenstrom
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Isarr Kronenstrom.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (hide armor) |
> | :FasHeart: HP | 117 (18d8 + 36) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 16 | 15 | 14 | 15 | 16 |
| **Mod** | +3 | +3 | +2 | +2 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** Common
**Skills:** Athletics +6, Intimidation +6, Perception +5, Stealth +6, Survival +5

---

### Traits

**Blood Frenzy.** Isarr has advantage on melee attack rolls against any creature that doesn't have all its hit points.

**Indomitable (3/Day).** Isarr can reroll a saving throw he fails. He must use the new roll.

**Keen Hearing and Smell.** Isarr has advantage on Wisdom (Perception) checks that rely on hearing or smell.


---

### Actions

**Multiattack.** Isarr makes three melee attacks.

**Sickle.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage, plus 13 (2d12) piercing damage if the target has no allies it can see within 10 feet of it.

**Heavy Crossbow.** Ranged Weapon Attack: +6 to hit, range 100/400 ft., one target. *Hit:* 8 (1d10 + 3) piercing damage.


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
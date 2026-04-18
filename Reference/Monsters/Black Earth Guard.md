---
type: pc
race: "Humanoid (human)"
class:
 - "Black Earth Guard"
subClass:
 - "CR 2"
cover: "Black Earth Guard.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/pota
---
###### Black Earth Guard
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Princes of the Apocalypse
___

> [!infobox|no-t right]
> ![[Black Earth Guard.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 39 (6d8 + 12) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Princes of the Apocalypse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 11 | 14 | 10 | 10 | 9 |
| **Mod** | +3 | +0 | +2 | +0 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common
**Skills:** Intimidation +1, Perception +2

---

### Actions

**Multiattack.** The guard makes two melee attacks.

**Morningstar.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage.


---

### Reactions

**Unyielding.** When the guard is subjected to an effect that would move it, knock it prone, or both, it can use its reaction to be neither moved nor knocked prone.


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
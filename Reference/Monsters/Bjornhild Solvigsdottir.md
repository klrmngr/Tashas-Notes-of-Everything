---
type: pc
race: "Humanoid (human)"
class:
 - "Bjornhild Solvigsdottir"
subClass:
 - "CR 5"
cover: "Bjornhild Solvigsdottir.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/idrotf
---
###### Bjornhild Solvigsdottir
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Bjornhild Solvigsdottir.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 (hide armor) |
> | :FasHeart: HP | 102 (12d8 + 48) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 11 | 18 | 14 | 11 | 14 |
| **Mod** | +4 | +0 | +4 | +2 | +0 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common, Yeti
**Skills:** Athletics +7, Intimidation +5, Survival +3

---

### Traits

**Auril's Blessing (3/Day).** When Bjornhild hits a creature with a weapon attack, the attack deals an extra 11 (2d10) cold damage.


---

### Actions

**Multiattack.** Bjornhild makes two melee attacks.

**Greataxe.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 10 (1d12 + 4) slashing damage, plus 11 (2d10) cold damage if Bjornhild uses Auril's Blessing.

**Spear.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage, or 8 (1d8 + 4) piercing damage if used with two hands to make a melee attack, plus 11 (2d10) cold damage if Bjornhild uses Auril's Blessing.


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
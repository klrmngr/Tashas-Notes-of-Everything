---
type: pc
race: "Humanoid (any race)"
class:
 - "Griffon Cavalry Rider"
subClass:
 - "CR 2"
cover: "Griffon Cavalry Rider.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/wdh
---
###### Griffon Cavalry Rider
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Griffon Cavalry Rider.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 17 (half plate armor) |
> | :FasHeart: HP | 58 (9d8 + 18) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 15 | 14 | 10 | 12 | 10 |
| **Mod** | +2 | +2 | +2 | +0 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** any one language (usually Common)
**Skills:** Animal Handling +3, Athletics +4, Perception +3

---

### Actions

**Lance.** Melee Weapon Attack: +4 to hit (with disadvantage against a target within 5 ft.), reach 10 ft., one target. *Hit:* 8 (1d12 + 2) piercing damage, or 11 (1d12 + 5) piercing damage while mounted.

**Dagger.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage. Or Ranged Weapon Attack: +4 to hit, range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.

**Feather Fall.** The rider wears a magic ring with which it can cast the feather fall spell on itself once as a reaction to falling. After the spell is cast, the ring becomes nonmagical.


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
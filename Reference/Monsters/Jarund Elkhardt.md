---
type: pc
race: "Humanoid (human)"
class:
 - "Jarund Elkhardt"
subClass:
 - "CR 5"
cover: "Jarund Elkhardt.png"
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
###### Jarund Elkhardt
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Jarund Elkhardt.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 (hide armor, shield) |
> | :FasHeart: HP | 104 (16d8 + 32) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 10 | 15 | 12 | 14 | 18 |
| **Mod** | +4 | +0 | +2 | +1 | +2 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Dwarvish
**Saving Throws:** Con +5, Wis +5
**Skills:** Athletics +7, Intimidation +7, Survival +5

---

### Traits

**Brute.** A melee weapon deals one extra die of its damage when Jarund hits with it (included in the attack).


---

### Actions

**Multiattack.** Jarund makes three melee attacks.

**Warhammer.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) bludgeoning damage, or 15 (2d10 + 4) bludgeoning damage when used with two hands.

**Shield.** Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. *Hit:* 11 (2d6 + 4) bludgeoning damage, and Jarund pushes the target 5 feet away from him if it's Large or smaller. Jarund then enters the space vacated by the target. If the target is pushed to within 5 feet of a creature friendly to Jarund, that creature can make an attack against the target as a reaction.

**Javelin.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage.


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
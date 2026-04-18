---
type: pc
race: "Humanoid (goblinoid)"
class:
 - "Bugbear Chief"
subClass:
 - "CR 3"
cover: "Bugbear Chief.png"
campaign:
locations:
tags:
  - race/goblinoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/mm
---
###### Bugbear Chief
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Bugbear Chief.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (goblinoid) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 (chain shirt, shield) |
> | :FasHeart: HP | 65 (10d8 + 20) |
> | :FasUserGroup: Race | Humanoid (goblinoid) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 14 | 14 | 11 | 12 | 11 |
| **Mod** | +3 | +2 | +2 | +0 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Common, Goblin
**Skills:** Intimidation +2, Stealth +6, Survival +3

---

### Traits

**Brute.** A melee weapon deals one extra die of its damage when the bugbear hits with it (included in the attack).

**Surprise Attack.** If the bugbear surprises a creature and hits it with an attack during the first round of combat, the target takes an extra 7 (2d6) damage from the attack.

**Heart of Hruggek.** The bugbear has advantage on saving throws against being charmed, frightened, paralyzed, poisoned, stunned, or put to sleep.


---

### Actions

**Multiattack.** The bugbear makes two melee attacks.

**Morningstar.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 11 (2d8 + 3) piercing damage.

**Javelin.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 9 (2d6 + 3) piercing damage in melee or 5 (1d6 + 3) piercing damage at range.


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
---
type: pc
race: "Fey"
class:
 - "Sprite"
subClass:
 - "CR 1/4"
cover: "Sprite.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/tiny
  - cr/1-4
  - source/mm
---
###### Sprite
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Sprite.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Tiny Fey |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 15 (leather armor) |
> | :FasHeart: HP | 2 (1d4) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 3 | 18 | 10 | 14 | 13 | 11 |
| **Mod** | -4 | +4 | +0 | +2 | +1 | +0 |

**Speed:** 10 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Elvish, Sylvan
**Skills:** Perception +3, Stealth +8

---

### Actions

**Longsword.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 1 slashing damage.

**Shortbow.** Ranged Weapon Attack: +6 to hit, range 40/160 ft., one target. *Hit:* 1 piercing damage, and the target must succeed on a DC 10 Constitution saving throw or become poisoned for 1 minute. If its saving throw result is 5 or lower, the poisoned target falls unconscious for the same duration, or until it takes damage or another creature takes an action to shake it awake.

**Heart Sight.** The sprite touches a creature and magically knows the creature's current emotional state. If the target fails a DC 10 Charisma saving throw, the sprite also knows the creature's alignment. Celestials, fiends, and undead automatically fail the saving throw.

**Invisibility.** The sprite magically turns invisible until it attacks or casts a spell, or until its concentration ends (as if concentrating on a spell). Any equipment the sprite wears or carries is invisible with it.


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
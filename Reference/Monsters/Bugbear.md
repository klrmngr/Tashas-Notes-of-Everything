---
type: pc
race: "Humanoid (goblinoid)"
class:
 - "Bugbear"
subClass:
 - "CR 1"
cover: "Bugbear.png"
campaign:
locations:
tags:
  - race/goblinoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/mm
---
###### Bugbear
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Bugbear.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (goblinoid) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (hide armor, shield) |
> | :FasHeart: HP | 27 (5d8 + 5) |
> | :FasUserGroup: Race | Humanoid (goblinoid) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 14 | 13 | 8 | 11 | 9 |
| **Mod** | +2 | +2 | +1 | -1 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, Goblin
**Skills:** Stealth +6, Survival +2

---

### Traits

**Brute.** A melee weapon deals one extra die of its damage when the bugbear hits with it (included in the attack).

**Surprise Attack.** If the bugbear surprises a creature and hits it with an attack during the first round of combat, the target takes an extra 7 (2d6) damage from the attack.


---

### Actions

**Morningstar.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 11 (2d8 + 2) piercing damage.

**Javelin.** Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 9 (2d6 + 2) piercing damage in melee or 5 (1d6 + 2) piercing damage at range.


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
---
type: pc
race: "Humanoid"
class:
 - "Dragon Army Soldier"
subClass:
 - "CR 1"
cover: "Dragon Army Soldier.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/dsotdq
---
###### Dragon Army Soldier
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Dragonlance: Shadow of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Dragon Army Soldier.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (scale mail, shield) |
> | :FasHeart: HP | 22 (4d8 + 4) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Dragonlance: Shadow of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 12 | 12 | 10 | 10 | 10 |
| **Mod** | +2 | +1 | +1 | +0 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Draconic
**Skills:** Athletics +4, Perception +2

---

### Traits

**Draconic Devotion.** While the soldier can see a Dragon that isn't hostile to it, the soldier has advantage on attack rolls.


---

### Actions

**Multiattack.** The soldier makes two Longsword or Javelin attacks.

**Longsword.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) slashing damage, or 7 (1d10 + 2) slashing damage if used with two hands, plus 2 (1d4) fire damage.

**Javelin.** Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage plus 2 (1d4) fire damage.


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
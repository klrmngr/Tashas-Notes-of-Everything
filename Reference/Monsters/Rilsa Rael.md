---
type: pc
race: "Humanoid (human)"
class:
 - "Rilsa Rael"
subClass:
 - "CR 3"
cover: "Rilsa Rael.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/bgdia
---
###### Rilsa Rael
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGDIA
___

> [!infobox|no-t right]
> ![[Rilsa Rael.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 (leather armor) |
> | :FasHeart: HP | 52 (8d8 + 16) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | BGDIA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 18 | 14 | 10 | 11 | 15 |
| **Mod** | +2 | +4 | +2 | +0 | +0 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Thieves' cant
**Saving Throws:** Dex +6, Wis +2
**Skills:** Acrobatics +6, Athletics +4, Deception +4, Perception +2, Sleight Of Hand +6, Stealth +6

---

### Traits

**Cunning Action.** On each of her turns in combat, Rilsa can use a bonus action to take the Dash, Disengage, or Hide action.

**Focus.** If Rilsa damages a creature with a weapon attack, she gains advantage on attack rolls against that target until the end of her next turn.

**Tactical Leadership.** As a bonus action, Rilsa chooses one creature she can see within 30 feet of her. The creature doesn't provoke opportunity attacks until the end of its next turn, provided it can hear Rilsa's commands.


---

### Actions

**Multiattack.** Rilsa makes three weapon attacks.

**Shortsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage.

**Dagger.** Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 6 (1d4 + 4) piercing damage.


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
---
type: pc
race: "Humanoid"
class:
 - "Dragon Army Officer"
subClass:
 - "CR 3"
cover: "Dragon Army Officer.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/dsotdq
---
###### Dragon Army Officer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Dragonlance: Shadow of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Dragon Army Officer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 19 (splint, shield) |
> | :FasHeart: HP | 65 (10d8 + 20) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Dragonlance: Shadow of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 15 | 12 | 14 | 12 |
| **Mod** | +3 | +2 | +2 | +1 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Common, Draconic
**Saving Throws:** Dex +4, Wis +4
**Skills:** Athletics +5, Perception +4

---

### Traits

**Draconic Devotion.** While the officer can see a Dragon that isn't hostile to it, the officer has advantage on attack rolls.


---

### Actions

**Multiattack.** The officer makes two Vicious Lance attacks and uses Assault Orders if it's available.

**Vicious Lance.** Melee Weapon Attack: +5 to hit, reach 10 ft., one target. *Hit:* 8 (1d10 + 3) piercing damage plus 2 (1d4) fire damage.

**Heavy Crossbow.** Ranged Weapon Attack: +4 to hit, range 100/400 ft., one target. *Hit:* 7 (1d10 + 2) piercing damage plus 5 (1d10) fire damage.

**Assault Orders (Recharge 5–6).** The officer shouts orders and targets up to two other creatures within 60 feet of itself. If a target has the Draconic Devotion trait and can hear the officer, the target can use its reaction to make one melee attack.


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
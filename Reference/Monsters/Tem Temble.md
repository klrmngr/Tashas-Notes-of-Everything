---
type: pc
race: "Humanoid (kender)"
class:
 - "Tem Temble"
subClass:
 - "CR —"
cover: "Tem Temble.png"
campaign:
locations:
tags:
  - race/kender
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/—
  - source/dsotdq
---
###### Tem Temble
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Dragonlance: Shadow of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Tem Temble.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Small Humanoid (kender) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 13 (leather armor) |
> | :FasHeart: HP | 11 (2d6 + 4) |
> | :FasUserGroup: Race | Humanoid (kender) |
> | :FasBook: Source | Dragonlance: Shadow of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 14 | 14 | 10 | 14 | 14 |
| **Mod** | -1 | +2 | +2 | +0 | +2 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Common, Kenderspeak
**Saving Throws:** Wis +4
**Skills:** Insight +4, Medicine +4, Perception +4, Sleight Of Hand +4, Stealth +4
**Condition Immunities:** frightened

---

### Traits

**Bonus Proficiencies.** Tem is proficient with simple weapons and light armor.


---

### Actions

**Hoopak.** Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 40/160 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage, or 4 (1d4 + 2) bludgeoning damage if Tem used the hoopak's sling to make a ranged attack.

**Taunt.** Tem launches an infuriating barrage of insults at a creature she can see within 60 feet of her. If the target can hear Tem, it must succeed on a DC 12 Wisdom saving throw or have disadvantage on attack rolls until the end of its next turn.


---

### Bonus Actions

**Elusive.** Tem takes the Disengage or Hide action.


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
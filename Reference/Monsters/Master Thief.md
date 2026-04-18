---
type: pc
race: "Humanoid"
class:
 - "Master Thief"
subClass:
 - "CR 5"
cover: "Master Thief.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/mpmm
---
###### Master Thief
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Master Thief.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (studded leather) |
> | :FasHeart: HP | 84 (13d8 + 26) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 18 | 14 | 11 | 11 | 12 |
| **Mod** | +0 | +4 | +2 | +0 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** any one language (usually Common) plus thieves' cant
**Saving Throws:** Dex +7, Int +3
**Skills:** Acrobatics +7, Athletics +3, Perception +3, Sleight Of Hand +7, Stealth +7

---

### Traits

**Evasion.** If the thief is subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, the thief instead takes no damage if it succeeds on the saving throw and only half damage if it fails, provided the thief isn't incapacitated.


---

### Actions

**Multiattack.** The thief makes three Shortsword or Shortbow attacks.

**Shortsword.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage plus 3 (1d6) poison damage.

**Shortbow.** Ranged Weapon Attack: +7 to hit, range 80/320 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage plus 3 (1d6) poison damage.


---

### Bonus Actions

**Cunning Action.** The thief takes the Dash, Disengage, or Hide action.


---

### Reactions

**Uncanny Dodge.** The thief halves the damage that it takes from an attack that hits it. The thief must be able to see the attacker.


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
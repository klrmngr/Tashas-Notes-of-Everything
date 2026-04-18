---
type: pc
race: "Humanoid (any race)"
class:
 - "Master Thief"
subClass:
 - "CR 5"
cover: "Master Thief.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/vgm
---
###### Master Thief
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Master Thief.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (studded leather) |
> | :FasHeart: HP | 83 (13d8 + 26) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 18 | 14 | 11 | 11 | 12 |
| **Mod** | +0 | +4 | +2 | +0 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** any one language (usually Common) plus Thieves' cant
**Saving Throws:** Dex +7, Int +3
**Skills:** Acrobatics +7, Athletics +3, Perception +3, Sleight Of Hand +7, Stealth +7

---

### Traits

**Cunning Action.** On each of its turns, the thief can use a bonus action to take the Dash, Disengage, or Hide action.

**Evasion.** If the thief is subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, the thief instead takes no damage if it succeeds on the saving throw, and only half damage if it fails.

**Sneak Attack (1/Turn).** The thief deals an extra 14 (4d6) damage when it hits a target with a weapon attack and has advantage on the attack roll, or when the target is within 5 feet of an ally of the thief that isn't incapacitated and the thief doesn't have disadvantage on the attack roll.


---

### Actions

**Multiattack.** The thief makes three attacks with its shortsword.

**Shortsword.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage.

**Light Crossbow.** Ranged Weapon Attack: +7 to hit, range 80/320 ft., one target. *Hit:* 8 (1d8 + 4) piercing damage.


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
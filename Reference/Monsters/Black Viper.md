---
type: pc
race: "Humanoid (human)"
class:
 - "Black Viper"
subClass:
 - "CR 5"
cover: "Black Viper.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/wdh
---
###### Black Viper
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Black Viper.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 16 (studded leather) |
> | :FasHeart: HP | 84 (13d8 + 26) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 18 | 14 | 11 | 11 | 12 |
| **Mod** | +0 | +4 | +2 | +0 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Thieves' cant
**Saving Throws:** Dex +7, Int +3
**Skills:** Acrobatics +7, Athletics +3, Perception +3, Sleight Of Hand +7, Stealth +7

---

### Traits

**Cunning Action.** On each of her turns, the Black Viper can use a bonus action to take the Dash, Disengage, or Hide action.

**Evasion.** If the Black Viper is subjected to an effect that allows her to make a Dexterity saving throw to take only half damage, she instead takes no damage if she succeeds on the saving throw, and only half damage if she fails. She can't use this trait if she's incapacitated.

**Sneak Attack (1/Turn).** The Black Viper deals an extra 14 (4d6) damage when she hits a target with a weapon attack and has advantage on the attack roll, or when the target is within 5 feet of an ally of the Black Viper that isn't incapacitated and the Black Viper doesn't have disadvantage on the attack roll.


---

### Actions

**Multiattack.** The Black Viper makes three attacks with her rapier.

**Rapier.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 4) piercing damage.

**Hand Crossbow.** Ranged Weapon Attack: +7 to hit, range 30/120 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage.


---

### Reactions

**Uncanny Dodge.** The Black Viper halves the damage that she takes from an attack that hits her. She must be able to see the attacker.


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
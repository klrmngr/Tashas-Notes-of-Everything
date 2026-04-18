---
type: pc
race: "Humanoid (any race)"
class:
 - "Assassin"
subClass:
 - "CR 8"
cover: "Assassin.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/8
  - source/mm
---
###### Assassin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Assassin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral Chaotic Evil |
> | :FasShield: AC | 15 (studded leather) |
> | :FasHeart: HP | 78 (12d8 + 24) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 16 | 14 | 13 | 11 | 10 |
| **Mod** | +0 | +3 | +2 | +1 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Thieves' cant plus any two languages
**Saving Throws:** Dex +6, Int +4
**Skills:** Acrobatics +6, Deception +3, Perception +3, Stealth +9
**Damage Resistances:** poison

---

### Traits

**Assassinate.** During its first turn, the assassin has advantage on attack rolls against any creature that hasn't taken a turn. Any hit the assassin scores against a surprised creature is a critical hit.

**Evasion.** If the assassin is subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, the assassin instead takes no damage if it succeeds on the saving throw, and only half damage if it fails.

**Sneak Attack (1/Turn).** The assassin deals an extra 14 (4d6) damage when it hits a target with a weapon attack and has advantage on the attack roll, or when the target is within 5 feet of an ally of the assassin that isn't incapacitated and the assassin doesn't have disadvantage on the attack roll.


---

### Actions

**Multiattack.** The assassin makes two shortsword attacks.

**Shortsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage, and the target must make a DC 15 Constitution saving throw, taking 24 (7d6) poison damage on a failed save, or half as much damage on a successful one.

**Light Crossbow.** Ranged Weapon Attack: +6 to hit, range 80/320 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage, and the target must make a DC 15 Constitution saving throw, taking 24 (7d6) poison damage on a failed save, or half as much damage on a successful one.


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
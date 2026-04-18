---
type: pc
race: "Humanoid (human)"
class:
 - "Imoen"
subClass:
 - "CR 8"
cover: "Imoen.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/8
  - source/mabjov
---
###### Imoen
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Imoen.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 16 (studded leather) |
> | :FasHeart: HP | 156 (24d8 + 48) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 18 | 14 | 14 | 10 | 14 |
| **Mod** | +0 | +4 | +2 | +2 | +0 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Thieves' cant, Undercommon
**Saving Throws:** Dex +7, Int +5
**Skills:** Acrobatics +7, Deception +5, Perception +3, Stealth +10
**Damage Resistances:** necrotic; poison

---

### Traits

**Evasion.** If Imoen is subjected to an effect that allows her to make a Dexterity saving throw to take only half damage, Imoen instead takes no damage if she succeeds on the saving throw, and only half damage if she fails.

**Sneak Attack (1/Turn).** Imoen deals an extra 14 (4d6) damage when she hits a target with a weapon attack and has advantage on the attack roll, or when the target is within 5 feet of an ally of Imoen that isn't incapacitated and Imoen doesn't have disadvantage on the attack roll.

**Spider Climb.** Imoen can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Sunlight Sensitivity.** While in sunlight, Imoen has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** Imoen makes two Shortsword attacks and one Hand Crossbow attack.

**Shortsword.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage plus 3 (1d6) poison damage.

**Hand Crossbow.** Ranged Weapon Attack: +7 to hit, range 30/210 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage plus 10 (3d6) poison damage.


---

### Bonus Actions

**Cunning Action.** Imoen takes the Dash, Disengage, or Hide action.


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
---
type: pc
race: "Humanoid (derro)"
class:
 - "Droki"
subClass:
 - "CR 2"
cover: "Droki.png"
campaign:
locations:
tags:
  - race/derro
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/2
  - source/oota
---
###### Droki
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Out of the Abyss
___

> [!infobox|no-t right]
> ![[Droki.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Humanoid (derro) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (studded leather) |
> | :FasHeart: HP | 31 (7d6 + 7) |
> | :FasUserGroup: Race | Humanoid (derro) |
> | :FasBook: Source | Out of the Abyss |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 16 | 13 | 10 | 5 | 16 |
| **Mod** | +0 | +3 | +1 | +0 | -3 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 7
**Languages:** Dwarvish, Undercommon
**Skills:** Stealth +5

---

### Traits

**Special Equipment.** Droki wears boots of speed.

**Insanity.** Droki has advantage on saving throws against being charmed or frightened.

**Sneak Attack (1/Turn).** Droki deals an extra 7 (2d6) damage when he hits a target with a weapon attack and has advantage on the attack roll, or when the target is within 5 feet of an ally of Droki that isn't incapacitated and Droki doesn't have disadvantage on the attack roll.

**Magic Resistance.** The derro has advantage on saving throws against spells and other magical effects.

**Sunlight Sensitivity.** While in sunlight, the derro has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** Droki makes two attacks with his shortsword

**Shortsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage. The sword is coated with serpent venom that wears off after the first hit. A target subjected to the venom must make a DC 11 Constitution saving throw, taking 10 (3d6) poison damage on a failed save, or half as much damage on a successful one.


---

### Reactions

**Parry.** Droki adds 3 to his AC against one melee attack that would hit him. To do so, Droki must see the attacker and be wielding a melee weapon.


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
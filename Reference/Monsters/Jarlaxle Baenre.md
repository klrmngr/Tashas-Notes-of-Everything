---
type: pc
race: "Humanoid (elf)"
class:
 - "Jarlaxle Baenre"
subClass:
 - "CR 15"
cover: "Jarlaxle Baenre.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/15
  - source/wdh
---
###### Jarlaxle Baenre
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Jarlaxle Baenre.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 24 (+3 leather armor, Suave Defense) |
> | :FasHeart: HP | 123 (19d8 + 38) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 22 | 14 | 20 | 16 | 19 |
| **Mod** | +1 | +6 | +2 | +5 | +3 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 18
**Languages:** Abyssal, Common, Draconic, Dwarvish, Elvish, Undercommon
**Saving Throws:** Dex +11, Wis +8
**Skills:** Acrobatics +11, Athletics +6, Deception +14, Perception +8, Sleight Of Hand +11, Stealth +16

---

### Traits

**Special Equipment.** Jarlaxle wears +3 leather armor, a hat of disguise, a bracer of flying daggers, a cloak of invisibility, a knave's eye patch, and a ring of truth telling. He wields a +3 rapier and carries a portable hole and a wand of web. His hat is adorned with a feather of diatryma summoning.

**Evasion.** If he is subjected to an effect that allows him to make a Dexterity saving throw to take only half damage, Jarlaxle instead takes no damage if he succeeds on the saving throw, and only half damage if he fails. He can't use this trait if he's incapacitated.

**Fey Ancestry.** Jarlaxle has advantage on saving throws against being charmed, and magic can't put him to sleep.

**Legendary Resistance (1/Day).** If Jarlaxle fails a saving throw, he can choose to succeed instead.

**Master Attuner.** Jarlaxle can attune to up to five magic items, and he can attune to magic items that normally require attunement by a sorcerer, warlock, or wizard.

**Sneak Attack (1/Turn).** Jarlaxle deals an extra 24 (7d6) damage when he hits a target with a weapon attack and has advantage on the attack roll, or when the target is within 5 feet of an ally of Jarlaxle's that isn't incapacitated and Jarlaxle doesn't have disadvantage on the attack roll.

**Suave Defense.** While Jarlaxle is wearing light or no armor and wielding no shield, his AC includes his Charisma modifier.

**Sunlight Sensitivity.** When not wearing his knave's eye patch, Jarlaxle has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** Jarlaxle makes three attacks with his +3 rapier or two attacks with daggers created by his bracer of flying daggers.

**+3 Rapier.** Melee Weapon Attack: +14 to hit, reach 5 ft., one target. *Hit:* 13 (1d8 + 9) piercing damage.

**Flying Dagger.** Ranged Weapon Attack: +11 to hit, range 20/60 ft., one target. *Hit:* 8 (1d4 + 6) piercing damage.


---

### Legendary Actions

### 

**Quick Step.** Jarlaxle moves up to his speed without provoking opportunity attacks.

**Attack (Costs 2 Actions).** Jarlaxle makes one attack with his +3 rapier or two attacks with daggers created by his bracer of flying daggers.


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
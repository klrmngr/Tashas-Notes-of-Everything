---
type: pc
race: "Humanoid (human)"
class:
 - "Mirt"
subClass:
 - "CR 9"
cover: "Mirt.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/wdh
---
###### Mirt
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Mirt.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 16 (bracers of defense) |
> | :FasHeart: HP | 153 (18d8 + 72) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 18 | 18 | 15 | 12 | 15 |
| **Mod** | +4 | +4 | +4 | +2 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common, Dwarvish
**Saving Throws:** Dex +8, Wis +5
**Skills:** Acrobatics +8, Athletics +8, Perception +5, Persuasion +6, Stealth +8

---

### Traits

**Special Equipment.** Mirt wears bracers of defense and a ring of regeneration. He wields a +1 longsword and a +1 dagger.

**Brute.** A melee weapon deals one extra die of its damage when Mirt hits with it (included in the attacks below).

**Evasion.** If he is subjected to an effect that allows him to make a Dexterity saving throw to take only half damage, Mirt instead takes no damage if he succeeds on the saving throw, and only half damage if he fails. He can't use this trait if he's incapacitated.

**Sneak Attack (1/Turn).** Mirt deals an extra 14 (4d6) damage when he hits a target with a weapon attack and has advantage on the attack roll, or when the target is within 5 feet of an ally of Mirt's that isn't incapacitated and Mirt doesn't have disadvantage on the attack roll.


---

### Actions

**Multiattack.** Mirt makes three attacks: two with his +1 longsword and one with his +1 dagger.

**+1 Longsword.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 14 (2d8 + 5) slashing damage, or 16 (2d10 + 5) slashing damage when used with two hands.

**+1 Dagger.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 10 (2d4 + 5) piercing damage. Or Ranged Weapon Attack: +9 to hit, range 20/60 ft., one target. *Hit:* 7 (1d4 + 5) piercing damage.


---

### Reactions

**Parry.** Mirt adds 2 to his AC against one melee attack that would hit him. To do so, Mirt must see the attacker and be wielding a melee weapon.


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
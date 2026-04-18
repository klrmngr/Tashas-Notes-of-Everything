---
type: pc
race: "Humanoid (human)"
class:
 - "Viari"
subClass:
 - "CR 5"
cover: "Viari.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/ai
---
###### Viari
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Acquisitions Incorporated
___

> [!infobox|no-t right]
> ![[Viari.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 18 (+1 studded leather); 19 while wielding two melee weapons |
> | :FasHeart: HP | 65 (10d8 + 20) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Acquisitions Incorporated |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 20 | 14 | 10 | 8 | 14 |
| **Mod** | +1 | +5 | +2 | +0 | -1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common, Draconic, Thieves' cant
**Saving Throws:** Dex +8, Int +3
**Skills:** Acrobatics +11, Athletics +7, Perception +5, Performance +5, Persuasion +5, Sleight Of Hand +11, Stealth +8

---

### Traits

**Evasion.** If Viari is subjected to an effect that allows him to make a Dexterity saving throw to take only half damage, he instead takes no damage if he succeeds on the saving throw, and only half damage if he fails. He can't use this trait if he's incapacitated.

**Second-Story Work.** Climbing does not cost Viari extra movement. Additionally, when he makes a running jump, the distance he covers increases by 5 feet.

**Sneak Attack (1/Turn).** Viari deals an extra 14 (4d6) damage when he hits a target with a weapon attack and has advantage on the attack roll, or when the target is within 5 feet of an ally of Viari that isn't incapacitated and Viari doesn't have disadvantage on the attack roll.


---

### Actions

**Multiattack.** Viari makes two attacks with his shortsword and two attacks with his rapier.

**+1 Shortsword.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 9 (1d6 + 6) piercing damage.

**Rapier.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 9 (1d8 + 5) piercing damage.

**Dagger.** Melee or Ranged Weapon Attack: +8 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 7 (1d4 + 5) piercing damage.


---

### Reactions

**Uncanny Dodge.** Viari halves the damage that he takes from an attack that hits him. He must be able to see the attacker.


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
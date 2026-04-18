---
type: pc
race: "Fey (harengon)"
class:
 - "Agdon Longscarf"
subClass:
 - "CR 2"
cover: "Agdon Longscarf.png"
campaign:
locations:
tags:
  - race/harengon
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/2
  - source/wbtw
---
###### Agdon Longscarf
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Agdon Longscarf.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Fey (harengon) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 19 (studded leather, shield) |
> | :FasHeart: HP | 36 (8d8) |
> | :FasUserGroup: Race | Fey (harengon) |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 20 | 11 | 11 | 14 | 16 |
| **Mod** | +0 | +5 | +0 | +0 | +2 | +3 |

**Speed:** 35 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common, Sylvan
**Saving Throws:** Dex +7, Wis +4
**Skills:** Acrobatics +7, Perception +6, Sleight Of Hand +7, Stealth +7

---

### Traits

**Evasion.** If Agdon is subjected to an effect that allows him to make a Dexterity saving throw to take only half damage, he instead takes no damage if he succeeds on the saving throw and only half damage if he fails, provided he isn't incapacitated.

**Standing Leap.** Agdon's long jump is up to 20 feet and his high jump is up to 10 feet, with or without a running start.


---

### Actions

**Multiattack.** Agdon makes two Branding Iron or Dagger attacks.

**Branding Iron.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 10 (3d6) fire damage, and the target is magically branded. Agdon is invisible to creatures branded in this way. The brand disappears after 24 hours, or it can be removed from a creature or object by any spell that ends a curse.

**Dagger.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 7 (1d4 + 5) piercing damage.


---

### Bonus Actions

**Quick Fingers.** Agdon targets one creature within 5 feet of him that he can see and makes a Dexterity (Sleight of Hand) check, with a DC equal to 1 + the target's passive Wisdom (Perception) score. On a successful check, Agdon pilfers one object weighing 1 pound or less that the target has in its possession but not in its grasp, without the target noticing the theft.


---

### Reactions

**Uncanny Dodge.** Agdon halves the damage that he takes from an attack that hits him. He must be able to see the attacker.


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
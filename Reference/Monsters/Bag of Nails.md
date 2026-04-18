---
type: pc
race: "Humanoid (tabaxi)"
class:
 - "Bag of Nails"
subClass:
 - "CR 8"
cover: "Bag of Nails.png"
campaign:
locations:
tags:
  - race/tabaxi
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/8
  - source/toa
---
###### Bag of Nails
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tomb of Annihilation
___

> [!infobox|no-t right]
> ![[Bag of Nails.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (tabaxi) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 15 (studded leather) |
> | :FasHeart: HP | 78 (12d8 + 24) |
> | :FasUserGroup: Race | Humanoid (tabaxi) |
> | :FasBook: Source | Tomb of Annihilation |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 16 | 14 | 13 | 11 | 10 |
| **Mod** | +0 | +3 | +2 | +1 | +0 | +0 |

**Speed:** 30 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Thieves' cant, Common, Dwarvish
**Saving Throws:** Dex +6, Int +4
**Skills:** Acrobatics +6, Deception +3, Perception +3, Stealth +9
**Damage Resistances:** poison

---

### Traits

**Feline Agility.** When Bag of Nails moves on its turn in combat, he can double his speed until the end of the turn. Once he uses this trait, Bag of Nails can't use it again until he moves 0 feet on one of his turns.

**Assassinate.** During his first turn, Bag of Nails has advantage on attack rolls against any creature that hasn't taken a turn. Any hit Bag of Nails scores against a surprised creature is a critical hit.

**Evasion.** If Bag of Nails is subjected to an effect that allows him to make a Dexterity saving throw to take only half damage, Bag of Nails instead takes no damage if he succeeds on the saving throw, and only half damage if it fails.

**Sneak Attack (1/Turn).** Bag of Nails deals an extra 14 (4d6) damage when he hits a target with a weapon attack and has advantage on the attack roll, or when the target is within 5 feet of an ally of his that isn't incapacitated and Bag of Nails doesn't have disadvantage on the attack roll.


---

### Actions

**Multiattack.** Bag of Nails makes two shortsword attacks.

**Claw.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 2 (1d4) slashing damage.

**Shortsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage, and the target must make a DC 15 Constitution saving throw, taking 24 (7d6) poison damage on a failed save, or half as much damage on a successful one.

**Longbow.** Ranged Weapon Attack: +6 to hit, range 150/600 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage, and the target must make a DC 15 Constitution saving throw, taking 24 (7d6) poison damage on a failed save, or half as much damage on a successful one.


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
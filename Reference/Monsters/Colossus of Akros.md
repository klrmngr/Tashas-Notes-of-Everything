---
type: pc
race: "Construct"
class:
 - "Colossus of Akros"
subClass:
 - "CR 23"
cover: "Colossus of Akros.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/gargantuan
  - cr/23
  - source/mot
---
###### Colossus of Akros
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Colossus of Akros.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 23 (50,000 XP) |
> | :RiSwordFill: Type | Gargantuan Construct |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 21 (natural armor) |
> | :FasHeart: HP | 350 (20d20 + 140) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 28 | 10 | 25 | 3 | 11 | 1 |
| **Mod** | +9 | +0 | +7 | -4 | +0 | -5 |

**Speed:** 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 17
**Languages:** understands Common and Celestial but can't speak
**Saving Throws:** Str +16, Con +14
**Skills:** Athletics +16, Perception +7
**Damage Immunities:** fire; poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned; stunned; unconscious

---

### Traits

**Crumbling Destruction.** When the colossus drops to 0 hit points, it crumbles and is destroyed. Any creature on the ground within 30 feet of the crumbling statue must make a DC 22 Dexterity saving throw, taking 22 (4d10) bludgeoning damage and 22 (4d10) fire damage on a failed save, or half as much damage on a successful one.

**Fire Absorption.** Whenever the colossus is subjected to fire damage, it takes no damage and instead regains a number of hit points equal to the fire damage dealt.

**Immutable Form.** The colossus is immune to any spell or effect that would alter its form.

**Magic Weapons.** The colossus's weapon attacks are magical.

**Siege Monster.** The colossus deals double damage to objects and structures.


---

### Actions

**Multiattack.** The colossus of Akros makes two melee attacks.

**Spear.** Melee or Ranged Weapon Attack: +16 to hit, reach 15 ft., or range 200/600 ft., one target. *Hit:* 23 (4d6 + 9) piercing damage, or 27 (4d8 + 9) piercing damage if used with two hands to make a melee attack. If the colossus makes a ranged attack with this spear, the spear magically returns to its hand after the attack.

**Sword.** Melee Weapon Attack: +16 to hit, reach 15 ft., one target. *Hit:* 36 (6d8 + 9) slashing damage.

**Flames of Akros (Recharge 6).** Magical flames issue from the colossus toward up to three creatures the colossus can see within 90 feet of it. Each target must make a DC 24 Dexterity saving throw, taking 36 (8d8) fire damage on a failed save, or half as much damage on a successful one. On a failed save, a target also magically catches fire for 1 minute. At the end of each of its turns thereafter, the burning target repeats the saving throw. It takes 18 (4d8) fire damage on a failed save, and the effect ends on a successful one.


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
---
type: pc
race: "Humanoid (human)"
class:
 - "Hlam"
subClass:
 - "CR 16"
cover: "Hlam.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/16
  - source/wdh
---
###### Hlam
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Hlam.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 22 (Unarmored Defense) |
> | :FasHeart: HP | 137 (25d8 + 25) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 24 | 13 | 14 | 21 | 14 |
| **Mod** | +0 | +7 | +1 | +2 | +5 | +2 |

**Speed:** 60 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** all spoken languages
**Saving Throws:** Str +5, Dex +12
**Skills:** Athletics +5, Religion +7
**Damage Immunities:** poison
**Condition Immunities:** charmed; frightened; poisoned; disease

---

### Traits

**Evasion.** If Hlam is subjected to an effect that allows him to make a Dexterity saving throw to take only half damage, he instead takes no damage if he succeeds on the saving throw, and only half damage if he fails. He can't use this trait if he's incapacitated.

**Magic Attacks.** Hlam's unarmed strikes are magical.

**Unarmored Defense.** While Hlam is wearing no armor and wielding no shield, his AC includes his Wisdom modifier.


---

### Actions

**Multiattack.** Hlam attacks three times using his unarmed strike, darts, or both.

**Unarmed Strike.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 12 (1d10 + 7) bludgeoning, magic damage. If the target is a creature, Hlam can choose one of the following additional effects:
The target must succeed on a DC 18 Strength saving throw or drop one item it is holding (Hlam's choice).
The target must succeed on a DC 18 Dexterity saving throw or be knocked prone.
The target must succeed on a DC 18 Constitution saving throw or be stunned until the end of Hlam's next turn.

**Dart.** Ranged Weapon Attack: +12 to hit, range 20/60 ft., one target. *Hit:* 9 (1d4 + 7) piercing damage.

**Quivering Palm (Recharge 6).** Melee Weapon Attack: +12 to hit, reach 5 ft., one creature. *Hit:* The target must make a DC 18 Constitution saving throw. On a failed save, the target is reduced to 0 hit points. On a successful save, the target takes 55 (10d10) necrotic damage.

**Wholeness of Body (Recharges after a Long Rest).** Hlam regains 60 hit points.


---

### Reactions

**Deflect Missile.** In response to being hit by a ranged weapon attack, Hlam deflects the missile. The damage he takes from the attack is reduced by 1d10 + 27. If the damage is reduced to 0, Hlam catches the missile if it's small enough to hold in one hand and he has a hand free.

**Slow Fall.** Hlam reduces the bludgeoning damage he takes from a fall by 100.


---

### Legendary Actions

### 

**Quick Step.** Hlam moves up to his speed without provoking opportunity attacks.

**Unarmed Strike (Costs 2 Actions).** Hlam makes one unarmed strike.

**Invisibility (Costs 3 Actions).** Hlam becomes invisible until the end of his next turn. The effect ends if Hlam attacks or casts a spell.


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
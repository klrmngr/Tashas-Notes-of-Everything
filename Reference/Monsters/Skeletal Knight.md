---
type: pc
race: "Undead"
class:
 - "Skeletal Knight"
subClass:
 - "CR 7"
cover: "Skeletal Knight.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/7
  - source/dsotdq
---
###### Skeletal Knight
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Dragonlance: Shadow of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Skeletal Knight.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (plate) |
> | :FasHeart: HP | 112 (15d8 + 45) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Dragonlance: Shadow of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 10 | 16 | 13 | 14 | 10 |
| **Mod** | +5 | +0 | +3 | +1 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** understands the languages it knew in life but can't speak
**Saving Throws:** Con +6, Wis +5
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Undead Fortitude.** If damage reduces the skeletal knight to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is bludgeoning or from a critical hit. On a success, the skeletal knight drops to 1 hit point instead.

**Unusual Nature.** The skeletal knight doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The skeletal knight makes three Enervating Blade or Throwing Axe attacks in any combination.

**Enervating Blade.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 15 (3d6 + 5) necrotic damage, and if the target is a creature, it can't regain hit points until the start of the skeletal knight's next turn.

**Throwing Axe.** Melee or Ranged Weapon Attack: +8 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 14 (2d8 + 5) slashing damage.


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
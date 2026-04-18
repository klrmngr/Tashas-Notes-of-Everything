---
type: pc
race: "Celestial"
class:
 - "Unicorn"
subClass:
 - "CR 5"
cover: "Unicorn.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/large
  - cr/5
  - source/mm
---
###### Unicorn
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Unicorn.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Celestial |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 67 (9d10 + 18) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 15 | 11 | 17 | 16 |
| **Mod** | +4 | +2 | +2 | +0 | +3 | +3 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Celestial, Elvish, Sylvan, telepathy 60 ft.
**Damage Immunities:** poison
**Condition Immunities:** charmed; paralyzed; poisoned

---

### Traits

**Charge.** If the unicorn moves at least 20 feet straight toward a target and then hits it with a horn attack on the same turn, the target takes an extra 9 (2d8) piercing damage. If the target is a creature, it must succeed on a DC 15 Strength saving throw or be knocked prone.

**Magic Resistance.** The unicorn has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The unicorn's weapon attacks are magical.


---

### Actions

**Multiattack.** The unicorn makes two attacks: one with its hooves and one with its horn.

**Hooves.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) bludgeoning damage.

**Horn.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) piercing damage.

**Healing Touch (3/Day).** The unicorn touches another creature with its horn. The target magically regains 11 (2d8 + 2) hit points. In addition, the touch removes all diseases and neutralizes all poisons afflicting the target.

**Teleport (1/Day).** The unicorn magically teleports itself and up to three willing creatures it can see within 5 feet of it, along with any equipment they are wearing or carrying, to a location the unicorn is familiar with, up to 1 mile away.


---

### Legendary Actions

### 

**Hooves.** The unicorn makes one attack with its hooves.

**Shimmering Shield (Costs 2 Actions).** The unicorn creates a shimmering, magical field around itself or another creature it can see within 60 feet of it. The target gains a +2 bonus to AC until the end of the unicorn's next turn.

**Heal Self (Costs 3 Actions).** The unicorn magically regains 11 (2d8 + 2) hit points.


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
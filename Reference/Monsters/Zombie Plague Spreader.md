---
type: pc
race: "Undead"
class:
 - "Zombie Plague Spreader"
subClass:
 - "CR 4"
cover: "Zombie Plague Spreader.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/4
  - source/vrgr
---
###### Zombie Plague Spreader
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Zombie Plague Spreader.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 78 (12d8 + 24) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 10 | 15 | 3 | 5 | 5 |
| **Mod** | +3 | +0 | +2 | -4 | -3 | -3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 7
**Languages:** understands the languages it knew in life but can't speak
**Damage Resistances:** necrotic
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; poisoned

---

### Traits

**Undead Fortitude.** If damage reduces the zombie to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the zombie drops to 1 hit point instead.

**Unusual Nature.** The zombie doesn't require air, food, drink, or sleep.

**Viral Aura.** Any creature that starts its turn within 10 feet of the plague spreader must make a DC 12 Constitution saving throw. On a failed save, the creature is poisoned and can't regain hit points until the end of its next turn. On a successful save, the creature is immune to this plague spreader's Viral Aura for 24 hours.


---

### Actions

**Multiattack.** The plague spreader makes two Slam attacks.

**Slam.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) bludgeoning damage plus 9 (2d8) necrotic damage.

**Virulent Miasma (1/Day).** The plague spreader releases toxic gas in a 30-foot-radius sphere centered on itself. Each creature in that area must make a DC 12 Constitution saving throw, taking 14 (4d6) poison damage on a failed save, or half as much damage on a successful one. A Humanoid reduced to 0 hit points by this damage dies and rises as a zombie (see its stat block in the Monster Manual) 1 minute later. The zombie acts immediately after the plague spreader in the initiative count.


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
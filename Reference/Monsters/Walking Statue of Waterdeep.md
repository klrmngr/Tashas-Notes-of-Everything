---
type: pc
race: "Construct"
class:
 - "Walking Statue of Waterdeep"
subClass:
 - "CR 18"
cover: "Walking Statue of Waterdeep.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/gargantuan
  - cr/18
  - source/wdh
---
###### Walking Statue of Waterdeep
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Walking Statue of Waterdeep.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 18 (20,000 XP) |
> | :RiSwordFill: Type | Gargantuan Construct |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 314 (17d20 + 136) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 30 | 8 | 27 | 1 | 10 | 1 |
| **Mod** | +10 | -1 | +8 | -5 | +0 | -5 |

**Speed:** 60 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 10
**Languages:** —
**Saving Throws:** Con +14
**Damage Immunities:** cold; fire; poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks not made with adamantine weapons
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned; stunned

---

### Traits

**Crumbling Colossus.** When the statue drops to 0 hit points, it crumbles and is destroyed. Any creature on the ground within 30 feet of the crumbling statue must make a DC 22 Dexterity saving throw, taking 22 (4d10) bludgeoning damage on a failed save, or half as much damage on a successful one.

**Immutable Form.** The statue is immune to any spell or effect that would alter its form.

**Magic Resistance.** The statue has advantage on saving throws against spells and other magical effects.

**Siege Monster.** The statue deals double damage to objects and structures.


---

### Actions

**Multiattack.** The statue makes two melee attacks.

**Slam.** Melee Weapon Attack: +16 to hit, reach 5 ft., one target. *Hit:* 29 (3d12 + 10) bludgeoning damage.

**Hurled Stone.** Ranged Weapon Attack: +16 to hit, range 200/800 ft., one target. *Hit:* 43 (6d10 + 10) bludgeoning damage.


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
---
type: pc
race: "Construct"
class:
 - "Stone Juggernaut"
subClass:
 - "CR 12"
cover: "Stone Juggernaut.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/12
  - source/toa
---
###### Stone Juggernaut
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tomb of Annihilation
___

> [!infobox|no-t right]
> ![[Stone Juggernaut.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 157 (15d10 + 75) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Tomb of Annihilation |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 12 | 15 | 14 | 14 | 16 |
| **Mod** | +3 | +1 | +2 | +2 | +2 | +3 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft., passive Perception 10
**Languages:** —
**Damage Immunities:** poison; bludgeoning, piercing, slashing from nonmagical attacks not made with adamantine weapons
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned; prone

---

### Traits

**Devastating Roll.** The juggernaut can move through the space of a prone creature. A creature whose space the juggernaut enters for the first time on a turn must make a DC 17 Dexterity saving throw, taking 55 (10d10) bludgeoning damage on a failed save, or half as much damage on a successful one.

**Immutable Form.** The juggernaut is immune to any spell or effect that would alter its form.

**Regeneration.** As long as it has 1 hit point left, the juggernaut magically regains all its hit points daily at dawn. The juggernaut is destroyed and doesn't regenerate if it drops to 0 hit points.

**Siege Monster.** The juggernaut deals double damage to objects and structures.


---

### Actions

**Slam.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 25 (3d12 + 6) bludgeoning damage. If the target is a Large or smaller creature, it must succeed on a DC 17 Strength saving throw or be knocked prone.


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
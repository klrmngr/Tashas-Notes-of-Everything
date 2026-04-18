---
type: pc
race: "Undead"
class:
 - "Giant Skeleton"
subClass:
 - "CR 7"
cover: "Giant Skeleton.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/huge
  - cr/7
  - source/tftyp
---
###### Giant Skeleton
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tales from the Yawning Portal
___

> [!infobox|no-t right]
> ![[Giant Skeleton.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Huge Undead |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 115 (10d12 + 50) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Tales from the Yawning Portal |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 10 | 20 | 4 | 6 | 6 |
| **Mod** | +5 | +0 | +5 | -3 | -2 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 8
**Languages:** understands Giant but can't speak
**Damage Vulnerabilities:** bludgeoning
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Evasion.** If the skeleton is subjected to an effect that allows it to make a saving throw to take only half damage, it instead takes no damage if it succeeds on the saving throw, and only half damage if it fails.

**Magic Resistance.** The skeleton has advantage on saving throws against spells and other magical effects.

**Turn Immunity.** The skeleton is immune to effects that turn undead.


---

### Actions

**Multiattack.** The skeleton makes three scimitar attacks.

**Scimitar.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 15 (3d6 + 5) slashing damage.


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
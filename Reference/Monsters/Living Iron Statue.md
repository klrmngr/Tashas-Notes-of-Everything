---
type: pc
race: "Construct"
class:
 - "Living Iron Statue"
subClass:
 - "CR 5"
cover: "Living Iron Statue.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/5
  - source/gos
---
###### Living Iron Statue
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Living Iron Statue.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 102 (12d8 + 48) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 18 | 6 | 10 | 5 |
| **Mod** | +3 | +2 | +4 | -2 | +0 | -3 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** understands the languages of its creator but can't speak
**Damage Vulnerabilities:** acid
**Damage Immunities:** lightning; poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Immutable Form.** The statue is immune to any spell or effect that would alter its form.


---

### Actions

**Multiattack.** The statue makes two attacks: one with its blade and one with its hammer.

**Blade.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) slashing damage.

**Hammer.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) bludgeoning damage, and the target is knocked prone.

**Whirl (Recharge 5–6).** The statue can use its action to spin at the waist, targeting creatures of its choice within 10 feet of it. Each target must make a DC 13 Dexterity saving throw, taking 19 (3d10 + 3) bludgeoning damage on a failed save, or half as much damage on a successful one.


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
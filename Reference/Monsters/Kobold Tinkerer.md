---
type: pc
race: "Humanoid"
class:
 - "Kobold Tinkerer"
subClass:
 - "CR 1/4"
cover: "Kobold Tinkerer.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1-4
  - source/dosi
---
###### Kobold Tinkerer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: DoSI
___

> [!infobox|no-t right]
> ![[Kobold Tinkerer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 10 (3d6) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | DoSI |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 7 | 14 | 10 | 15 | 7 | 9 |
| **Mod** | -2 | +2 | +0 | +2 | -2 | -1 |

**Speed:** 30 ft., fly 10 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, Draconic
**Skills:** Arcana +4, Perception +0

---

### Traits

**Inquiring Mind (1/Day).** The kobold can cast detect magic, requiring no spell components and using Intelligence as the spellcasting ability.

**Pack Tactics.** The kobold has advantage on an attack roll against a creature if at least one of its allies is within 5 feet of the creature and the ally isn't incapacitated.

**Sunlight Sensitivity.** While in sunlight, the kobold has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Dagger.** Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.

**Alchemical Flame (Recharge 6).** The kobold unleashes fire in a 15-foot cone. Each creature in that area must make a DC 12 Dexterity saving throw, taking 10 (3d6) fire damage on a failed saving throw, or half as much damage on a successful one.


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
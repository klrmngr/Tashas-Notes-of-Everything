---
type: pc
race: "Humanoid (kobold)"
class:
 - "Kobold Scale Sorcerer"
subClass:
 - "CR 1"
cover: "Kobold Scale Sorcerer.png"
campaign:
locations:
tags:
  - race/kobold
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1
  - source/vgm
---
###### Kobold Scale Sorcerer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Kobold Scale Sorcerer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Small Humanoid (kobold) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 27 (5d6 + 10) |
> | :FasUserGroup: Race | Humanoid (kobold) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 7 | 15 | 14 | 10 | 9 | 14 |
| **Mod** | -2 | +2 | +2 | +0 | -1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 9
**Languages:** Common, Draconic
**Skills:** Arcana +2, Medicine +1

---

### Traits

**Sorcery Points.** The kobold has 3 sorcery points. It regains all its spent sorcery points when it finishes a long rest. It can spend its sorcery points on the following options:
Heightened Spell: When it casts a spell that forces a creature to a saving throw to resist the spell's effects, the kobold can spend 3 sorcery points to give one target of the spell disadvantage on its first saving throw against the spell.
Subtle Spell: When the kobold casts a spell, it can spend 1 sorcery point to cast the spell without any somatic or verbal components.

**Pack Tactics.** The kobold has advantage on an attack roll against a creature it at least one of the kobold's allies is within 5 feet of the creature and the ally isn't incapacitated.

**Sunlight Sensitivity.** While in sunlight, the kobold has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Dagger.** Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.


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
---
type: pc
race: "Humanoid"
class:
 - "Kobold Scale Sorcerer"
subClass:
 - "CR 1"
cover: "Kobold Scale Sorcerer.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1
  - source/mpmm
---
###### Kobold Scale Sorcerer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Kobold Scale Sorcerer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 27 (5d6 + 10) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

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

**Pack Tactics.** The kobold has advantage on an attack roll against a creature if at least one of the kobold's allies is within 5 feet of the creature and the ally isn't incapacitated.

**Sunlight Sensitivity.** While in sunlight, the kobold has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** The kobold makes two Dagger or Chromatic Bolt attacks. It can replace one attack with a use of Spellcasting.

**Dagger.** Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.

**Chromatic Bolt.** Ranged Spell Attack: +4 to hit, range 60 feet, one target. *Hit:* 9 (2d6 + 2) of a type of the kobold's choice: acid, cold, fire, lightning, poison, or thunder.


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
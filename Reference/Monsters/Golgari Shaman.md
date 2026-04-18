---
type: pc
race: "Humanoid (elf)"
class:
 - "Golgari Shaman"
subClass:
 - "CR 5"
cover: "Golgari Shaman.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/ggr
---
###### Golgari Shaman
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Golgari Shaman.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 (hide armor) |
> | :FasHeart: HP | 88 (16d8 + 16) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 15 | 12 | 12 | 17 | 16 |
| **Mod** | +0 | +2 | +1 | +1 | +3 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Elvish
**Saving Throws:** Con +4, Wis +6
**Skills:** Arcana +4, Insight +6, Nature +4, Religion +4

---

### Traits

**Fey Ancestry.** The shaman has advantage on saving throws against being charmed, and magic can't put it to sleep.


---

### Actions

**Quarterstaff.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) bludgeoning damage, or 6 (1d8 + 2) bludgeoning damage if used with two hands.

**Fungal Rot.** Melee Spell Attack: +6 to hit, reach 5 ft., one target. *Hit:* 9 (2d8) necrotic damage, and the target must make a DC 14 Constitution saving throw, taking 18 (4d8) poison damage on a failed save, or half as much damage on a successful one.


---

### Reactions

**Feed on Death.** When a creature within 30 feet of the shaman drops to 0 hit points, the shaman gains 5 (1d10) temporary hit points.


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
---
type: pc
race: "Humanoid (gnome)"
class:
 - "Rock Gnome Recluse"
subClass:
 - "CR 1/4"
cover: "Rock Gnome Recluse.png"
campaign:
locations:
tags:
  - race/gnome
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1-4
  - source/dip
---
###### Rock Gnome Recluse
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: DIP
___

> [!infobox|no-t right]
> ![[Rock Gnome Recluse.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Humanoid (gnome) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 10; 13 with mage armor |
> | :FasHeart: HP | 7 (2d6) |
> | :FasUserGroup: Race | Humanoid (gnome) |
> | :FasBook: Source | DIP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 11 | 10 | 15 | 10 | 13 |
| **Mod** | -2 | +0 | +0 | +2 | +0 | +1 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, Gnomish
**Skills:** Arcana +4, History +4

---

### Traits

**Gnome Cunning.** The gnome has advantage on Intelligence, Wisdom, and Charisma saving throws against magic.


---

### Actions

**Magic Missile (Expends a 1st-Level Spell Slot).** The gnome creates three magical darts. Each dart hits a creature the gnome chooses within 120 feet of it and deals 3 (1d4 + 1) force damage.

**Ray of Frost.** Ranged Spell Attack: +4 to hit, range 60 ft., one creature. *Hit:* 4 (1d8) cold damage, and the target's speed is reduced by 10 feet until the start of the gnome's next turn.


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
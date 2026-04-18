---
type: pc
race: "Humanoid (gnome)"
class:
 - "Spellix Romwod"
subClass:
 - "CR 1/2"
cover: "Spellix Romwod.png"
campaign:
locations:
tags:
  - race/gnome
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1-2
  - source/idrotf
---
###### Spellix Romwod
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Spellix Romwod.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Small Humanoid (gnome) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 14 (hide armor) |
> | :FasHeart: HP | 33 (6d6 + 12) |
> | :FasUserGroup: Race | Humanoid (gnome) |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 15 | 14 | 15 | 9 | 16 |
| **Mod** | -2 | +2 | +2 | +2 | -1 | +3 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 9
**Languages:** Common, Draconic, Elvish, Gnomish, Goblin
**Skills:** Arcana +4, Deception +5, History +4

---

### Traits

**Gnome Cunning.** Spellix has advantage on all Intelligence, Wisdom, and Charisma saving throws against magic.


---

### Actions

**Shocking Grasp (Cantrip).** Melee Spell Attack: +5 to hit (with advantage on the attack roll if the target is wearing armor made of metal), reach 5 ft., one creature. *Hit:* 4 (1d8) lightning damage, and the target can't take reactions until the start of its next turn.

**Fire Bolt (Cantrip).** Ranged Spell Attack: +5 to hit, range 120 ft., one target. *Hit:* 5 (1d10) fire damage. A flammable object hit by this spell ignites if it isn't being worn or carried.


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
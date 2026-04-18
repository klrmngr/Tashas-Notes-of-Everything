---
type: pc
race: "Fey (goblinoid)"
class:
 - "Hobgoblin Devastator"
subClass:
 - "CR 4"
cover: "Hobgoblin Devastator.png"
campaign:
locations:
tags:
  - race/goblinoid
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/4
  - source/mpmm
---
###### Hobgoblin Devastator
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Hobgoblin Devastator.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Fey (goblinoid) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 13 (studded leather) |
> | :FasHeart: HP | 45 (7d8 + 14) |
> | :FasUserGroup: Race | Fey (goblinoid) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 12 | 14 | 16 | 13 | 11 |
| **Mod** | +1 | +1 | +2 | +3 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Common, Goblin
**Skills:** Arcana +5

---

### Traits

**Army Arcana.** When the hobgoblin casts a spell that causes damage or that forces other creatures to make a saving throw, it can choose itself and any number of allies to be immune to the damage caused by the spell and to succeed on the required saving throw.


---

### Actions

**Multiattack.** The hobgoblin makes two Quarterstaff or Devastating Bolt attacks.

**Quarterstaff.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 4 (1d6 + 1) bludgeoning damage, or 5 (1d8 + 1) bludgeoning damage if used with two hands, plus 13 (3d8) force damage.

**Devastating Bolt.** Ranged Spell Attack: +5 to hit, range 60 ft., one target. *Hit:* 21 (4d8 + 3) force damage, and the target is knocked prone.


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
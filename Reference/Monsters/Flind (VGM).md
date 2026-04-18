---
type: pc
race: "Humanoid (gnoll)"
class:
 - "Flind"
subClass:
 - "CR 9"
cover: "Flind.png"
campaign:
locations:
tags:
  - race/gnoll
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/vgm
---
###### Flind
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Flind.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (gnoll) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (chain mail) |
> | :FasHeart: HP | 127 (15d8 + 60) |
> | :FasUserGroup: Race | Humanoid (gnoll) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 10 | 19 | 11 | 13 | 12 |
| **Mod** | +5 | +0 | +4 | +0 | +1 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** Abyssal, Gnoll
**Saving Throws:** Con +8, Wis +5
**Skills:** Intimidation +5, Perception +5

---

### Traits

**Aura of Blood Thirst.** If the flind isn't incapacitated, any creature with the Rampage trait can make a bite attack as a bonus action while within 10 feet of the flind.


---

### Actions

**Multiattack.** The flind makes three attacks: one with each of its different flail attacks or three with its longbow.

**Flail of Madness.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 10 (1d10 + 5) bludgeoning damage, and the target must make a DC 16 Wisdom saving throw. On a failed save, the target must make a melee attack against a random target within its reach on its next turn. If it has no targets within its reach even after moving, it loses its action on that turn.

**Flail of Pain.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 10 (1d10 + 5) bludgeoning damage plus 22 (4d10) psychic damage.

**Flail of Paralysis.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 10 (1d10 + 5) bludgeoning damage, and the target must succeed on a DC 16 Constitution saving throw or be paralyzed until the end of its next turn.

**Longbow.** Ranged Weapon Attack: +4 to hit, range 150/600 ft., one target. *Hit:* 4 (1d8) piercing damage.


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
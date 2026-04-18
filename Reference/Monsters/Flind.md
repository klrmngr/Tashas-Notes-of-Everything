---
type: pc
race: "Fiend (gnoll)"
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
  - type/fiend
  - size/medium
  - cr/9
  - source/mpmm
---
###### Flind
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Flind.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Fiend (gnoll) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (breastplate) |
> | :FasHeart: HP | 127 (15d8 + 60) |
> | :FasUserGroup: Race | Fiend (gnoll) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 14 | 19 | 11 | 13 | 12 |
| **Mod** | +5 | +2 | +4 | +0 | +1 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** Gnoll, Abyssal
**Saving Throws:** Con +8, Wis +5
**Skills:** Intimidation +5, Perception +5

---

### Traits

**Aura of Blood Thirst.** If the flind isn't incapacitated, any creature with the Rampage trait can make a Bite attack as a bonus action while within 10 feet of the flind.


---

### Actions

**Multiattack.** The flind makes one Flail of Chaos attack, one Flail of Pain attack, and one Flail of Paralysis attack, or it makes three Longbow attacks.

**Flail of Chaos.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 10 (1d10 + 5) bludgeoning damage, and the target must make a DC 16 Wisdom saving throw. On a failed save, the target must use its reaction, if available, to make one melee attack against a random creature, other than the flind, within its reach. If there's no creature within reach, the target instead moves half its speed in a random direction.

**Flail of Pain.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 10 (1d10 + 5) bludgeoning damage plus 16 (3d10) psychic damage.

**Flail of Paralysis.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 10 (1d10 + 5) bludgeoning damage, and the target must succeed on a DC 16 Constitution saving throw or be paralyzed until the end of its next turn.

**Longbow.** Ranged Weapon Attack: +6 to hit, range 150/600 ft., one target. *Hit:* 6 (1d8 + 2) piercing damage.


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
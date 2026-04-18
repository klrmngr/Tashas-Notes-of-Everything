---
type: pc
race: "Giant (hill giant)"
class:
 - "Mouth of Grolantor"
subClass:
 - "CR 6"
cover: "Mouth of Grolantor.png"
campaign:
locations:
tags:
  - race/hill giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/6
  - source/vgm
---
###### Mouth of Grolantor
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Mouth of Grolantor.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Huge Giant (hill giant) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 105 (10d12 + 40) |
> | :FasUserGroup: Race | Giant (hill giant) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 10 | 18 | 5 | 7 | 5 |
| **Mod** | +5 | +0 | +4 | -3 | -2 | -3 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Giant
**Skills:** Perception +1
**Condition Immunities:** frightened

---

### Traits

**Mouth of Madness.** The giant is immune to confusion spells and similar magic.
On each of its turns, the giant uses all its movement to move toward the nearest creature or whatever else it might perceive as food. Roll a d10 at the start of each of the giant's turns to determine its action for that turn:
1–3. The giant makes three attacks with its fists against one random target within its reach. If no other creatures are within its reach, the giant flies into a rage and gains advantage on all attack rolls until the end of its next turn.
4–5. The giant makes one attack with its fist against every creature within its reach. If no other creatures are within its reach, the giant makes one fist attack against itself.
6–7. The giant makes one attack with its bite against one random target within its reach. If no other creatures are within its reach, its eyes glaze over and it becomes stunned until the start of its next turn.
8–10. The giant makes three attacks against one random target within its reach: one attack with its bite and two with its fists. If no other creatures are within its reach, the giant flies into a rage and gains advantage on all attack rolls until the end of its next turn.


---

### Actions

**Bite.** Melee Weapon Attack: +8 to hit, reach 5 ft., one creature. *Hit:* 15 (3d6 + 5) piercing damage, and the giant magically regains hit points equal to the damage dealt.

**Fist.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 18 (3d8 + 5) bludgeoning damage.


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
---
type: pc
race: "Giant"
class:
 - "Cloud Giant Smiling One"
subClass:
 - "CR 11"
cover: "Cloud Giant Smiling One.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/11
  - source/mpmm
---
###### Cloud Giant Smiling One
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Cloud Giant Smiling One.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 250 (20d12 + 120) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 12 | 22 | 15 | 16 | 17 |
| **Mod** | +8 | +1 | +6 | +2 | +3 | +3 |

**Speed:** 40 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** passive Perception 21
**Languages:** Common, Giant
**Saving Throws:** Con +10, Int +6, Cha +7
**Skills:** Deception +11, Insight +7, Perception +11, Sleight Of Hand +9

---

### Traits

**Control Weather (8th-level Spell).** The giant can cast the control weather spell, requiring no material components and using Charisma as the spellcasting ability.


---

### Actions

**Multiattack.** The giant makes two Slam attacks or two Telekinetic Strike attacks.

**Slam.** Melee Weapon Attack: +12 to hit, reach 10 ft., one target. *Hit:* 21 (3d8 + 8) bludgeoning damage plus 5 (1d10) psychic damage.

**Telekinetic Strike.** Ranged Spell Attack: +7 to hit, range 240 ft., one target. *Hit:* 25 (4d10 + 3) force damage.

**Change Shape.** The giant magically transforms to look and feel like a Beast or a Humanoid it has seen or to return to its true form. Any equipment the giant is wearing or carrying is absorbed by the new form. Its statistics, other than its size, don't change. It reverts to its true form if it dies.


---

### Bonus Actions

**Cloud Step (Recharge 4–6).** The giant teleports, along with any equipment it is wearing or carrying, up to 60 feet to an unoccupied space it can see.


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
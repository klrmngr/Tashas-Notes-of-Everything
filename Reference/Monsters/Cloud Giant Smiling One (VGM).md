---
type: pc
race: "Giant (cloud giant)"
class:
 - "Cloud Giant Smiling One"
subClass:
 - "CR 11"
cover: "Cloud Giant Smiling One.png"
campaign:
locations:
tags:
  - race/cloud giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/11
  - source/vgm
---
###### Cloud Giant Smiling One
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Cloud Giant Smiling One.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Huge Giant (cloud giant) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 262 (21d12 + 128) |
> | :FasUserGroup: Race | Giant (cloud giant) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 12 | 22 | 15 | 16 | 17 |
| **Mod** | +8 | +1 | +6 | +2 | +3 | +3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 17
**Languages:** Common, Giant
**Saving Throws:** Con +10, Int +6, Wis +7
**Skills:** Deception +11, Insight +7, Perception +7, Sleight Of Hand +9

---

### Traits

**Keen Smell.** The giant has advantage on Wisdom (Perception) checks that rely on smell.


---

### Actions

**Multiattack.** The giant makes two attacks with its morningstar.

**Morningstar.** Melee Weapon Attack: +12 to hit, reach 10 ft., one target. *Hit:* 21 (3d8 + 8) bludgeoning damage. The attack deals an extra 14 (4d6) damage if the giant has advantage on the attack roll.

**Rock.** Ranged Weapon Attack: +12 to hit, range 60/240 ft., one target. *Hit:* 30 (4d10 + 8) bludgeoning damage. The attack deals an extra 14 (4d6) damage if the giant has advantage on the attack roll.

**Change Shape.** The giant magically polymorphs into a beast or humanoid it has seen, or back into its true form. Any equipment the giant is wearing or carrying is absorbed by the new form. Its statistics, other than its size, are the same in each form. It reverts to its true form if it dies.


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
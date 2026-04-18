---
type: pc
race: "Fey"
class:
 - "Korred"
subClass:
 - "CR 7"
cover: "Korred.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/small
  - cr/7
  - source/vgm
---
###### Korred
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Korred.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Small Fey |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 102 (12d6 + 60) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 14 | 20 | 10 | 15 | 9 |
| **Mod** | +6 | +2 | +5 | +0 | +2 | -1 |

**Speed:** 30 ft., burrow 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., tremorsense 120 ft., passive Perception 15
**Languages:** Dwarvish, Gnomish, Sylvan, Terran, Undercommon
**Skills:** Athletics +9, Perception +5, Stealth +5
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks

---

### Traits

**Command Hair.** The korred has at least one 50-foot-long rope woven out of its hair. As a bonus action, the korred commands one such rope within 30 feet of it to move up to 20 feet and entangle a Large or smaller creature that the korred can see. The target must succeed on a DC 13 Dexterity saving throw or become grappled by the rope (escape DC 13). Until this grapple ends. the target is restrained. The korred can use a bonus action to release the target, which is also freed if the korred dies or becomes incapacitated.
A rope of korred hair has AC 20 and 20 hit points. It regains 1 hit point at the start of each of the korred's turns while it has at least 1 hit point and the korred is alive. If the rope drops to 0 hit points, it is destroyed.

**Stone Camouflage.** The korred has advantage on Dexterity (Stealth) checks made to hide in rocky terrain.

**Stone's Strength.** While on the ground, the korred deals 2 extra dice of damage with any weapon attack (included in its attacks).


---

### Actions

**Multiattack.** The korred makes two attacks with its greatclub or hurls two rocks.

**Greatclub.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 10 (1d8 + 6) bludgeoning damage, or 19 (3d8 + 6) bludgeoning damage if the korred is on the ground.

**Rock.** Ranged Weapon Attack: +9 to hit, range 60/120 ft., one target. *Hit:* 15 (2d8 + 6) bludgeoning damage, or 24 (4d8 + 6) bludgeoning damage if the korred is on the ground.


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
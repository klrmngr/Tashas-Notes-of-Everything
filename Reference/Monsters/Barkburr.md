---
type: pc
race: "Plant"
class:
 - "Barkburr"
subClass:
 - "CR 3"
cover: "Barkburr.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/small
  - cr/3
  - source/qftis
---
###### Barkburr
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: QftIS
___

> [!infobox|no-t right]
> ![[Barkburr.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Small Plant |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 52 (8d6 + 24) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | QftIS |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 6 | 16 | 1 | 15 | 1 |
| **Mod** | +3 | -2 | +3 | -5 | +2 | -5 |

**Speed:** 10 ft., climb 10 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (can't see beyond this radius), passive Perception 12
**Languages:** —
**Skills:** Athletics +5
**Damage Immunities:** psychic
**Condition Immunities:** blinded; charmed; deafened; frightened

---

### Traits

**False Appearance.** If the barkburr is motionless at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the barkburr move or act, that creature must succeed on a DC 18 Intelligence (Investigation) check to discern that the barkburr is animate.

**Springing Leap.** With or without a running start, the barkburr's high jump is up to 15 feet, and its long jump is up to 30 feet. The barkburr's jumps can exceed its speed if its speed isn't 0.


---

### Actions

**Multiattack.** The barkburr makes two Poison Barb attacks and uses Lignify if able.

**Poison Barb.** Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. *Hit:* 5 (1d4 + 3) piercing damage plus 7 (2d6) poison damage, and the barkburr attaches to the target. While the barkburr is attached, it can't make Poison Barb attacks, and the target has the restrained condition as its body begins to transform into wood.
An attached barkburr can detach itself by spending 5 feet of its movement on its turn. A creature that can reach the barkburr, including the target, can use its action to detach the barkburr by making a successful DC 13 Strength (Athletics) check.

**Lignify.** The barkburr targets the creature it is attached to, and the target must make a DC 13 Constitution saving throw. On a failed save, the target has the petrified condition until freed by the Greater Restoration spell or another effect, except it turns into a tree instead of stone. Any equipment the target is wearing or carrying is absorbed into the tree's bark.


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
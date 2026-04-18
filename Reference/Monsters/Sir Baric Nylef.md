---
type: pc
race: "Humanoid (human)"
class:
 - "Sir Baric Nylef"
subClass:
 - "CR —"
cover: "Sir Baric Nylef.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/—
  - source/skt
---
###### Sir Baric Nylef
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Sir Baric Nylef.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 52 (8d8 + 16) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 11 | 14 | 11 | 15 | 15 |
| **Mod** | +4 | +0 | +2 | +0 | +2 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common
**Skills:** Insight +4, Investigation +2, Medicine +4, Survival +4

---

### Traits

**Brave.** Baric has advantage on saving throws against being frightened.

**Roleplaying Information.** As a knight of the Order of the Gauntlet, Sir Baric has sworn oaths to catch evildoers and bring them to justice. His current quarry is a dwarf brigand, Worvil "the Weevil" Forkbeard, who is rumored to be hiding in Icewind Dale. In addition to his gear, Sir Baric has an unarmored warhorse, Henry.
Ideal: "Evil must not be allowed to thrive in this world."
Bond: "Tyr is my lord; the order, my family. Through my actions, I shall honor both."
Flaw: "I'm not afraid to die. When Tyr finally calls me, I'll go to him happily."


---

### Actions

**Maul.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) bludgeoning damage.

**Heavy Crossbow.** Ranged Weapon Attack: +2 to hit, range 100/400 ft., one target. *Hit:* 5 (1d10) piercing damage. Baric carries twenty crossbow bolts.


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
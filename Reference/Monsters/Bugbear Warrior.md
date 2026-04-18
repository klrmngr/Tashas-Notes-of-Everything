---
type: pc
race: "Fey (goblinoid)"
class:
 - "Bugbear Warrior"
subClass:
 - "CR 1"
cover: "Bugbear Warrior.png"
campaign:
locations:
tags:
  - race/goblinoid
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/1
  - source/xmm
---
###### Bugbear Warrior
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Bugbear Warrior.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Fey (goblinoid) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Fey (goblinoid) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 14 | 13 | 8 | 11 | 9 |
| **Mod** | +2 | +2 | +1 | -1 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** Common, Goblin
**Skills:** Stealth +6, Survival +2

---

### Traits

**Abduct.** The bugbear needn't spend extra movement to move a creature it is grappling.


---

### Actions

**Grab.** m +4, reach 10 ft. *Hit:* 9 (2d6 + 2) Bludgeoning damage. If the target is a Medium or smaller creature, it has the Grappled condition (escape DC 12).

**Light Hammer.** m,r +4 (with Advantage if the target is Grappled by the bugbear), reach 10 ft. or range 20/60 ft. *Hit:* 9 (3d4 + 2) Bludgeoning damage.


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
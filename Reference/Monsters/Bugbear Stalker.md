---
type: pc
race: "Fey (goblinoid)"
class:
 - "Bugbear Stalker"
subClass:
 - "CR 3"
cover: "Bugbear Stalker.png"
campaign:
locations:
tags:
  - race/goblinoid
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/3
  - source/xmm
---
###### Bugbear Stalker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Bugbear Stalker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Fey (goblinoid) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 65 (10d8 + 20) |
> | :FasUserGroup: Race | Fey (goblinoid) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 14 | 14 | 11 | 12 | 11 |
| **Mod** | +3 | +2 | +2 | +0 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 11
**Languages:** Common, Goblin
**Saving Throws:** Con +4, Wis +3
**Skills:** Stealth +6, Survival +3

---

### Traits

**Abduct.** The bugbear needn't spend extra movement to move a creature it is grappling.


---

### Actions

**Multiattack.** The bugbear makes two Javelin or Morningstar attacks.

**Javelin.** m,r +5, reach 10 ft. or range 30/120 ft. *Hit:* 13 (3d6 + 3) Piercing damage.

**Morningstar.** m +5 (with Advantage if the target is Grappled by the bugbear), reach 10 ft. *Hit:* 12 (2d8 + 3) Piercing damage.


---

### Bonus Actions

**Quick Grapple.** dex DC 13, one Medium or smaller creature the bugbear can see within 10 feet.  The target has the Grappled condition (escape DC 13).


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
---
type: pc
race: "Fey (hag)"
class:
 - "Endelyn Moongrave"
subClass:
 - "CR 6"
cover: "Endelyn Moongrave.png"
campaign:
locations:
tags:
  - race/hag
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/6
  - source/wbtw
---
###### Endelyn Moongrave
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Endelyn Moongrave.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Fey (hag) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 114 (12d8 + 60) |
> | :FasUserGroup: Race | Fey (hag) |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 13 | 20 | 13 | 10 | 17 |
| **Mod** | +5 | +1 | +5 | +1 | +0 | +3 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** truesight 60 ft., passive Perception 13
**Languages:** Common, Elvish, Sylvan
**Saving Throws:** Con +8, Int +4, Wis +3, Cha +6
**Skills:** Arcana +7, Deception +6, Perception +3, Stealth +4

---

### Traits

**Boon of Immortality.** Endelyn is immune to any effect that would age her, and she can't die from old age.

**Eclipsed Doom.** Endelyn can be killed only if she is reduced to 0 hit points during a solar eclipse or while she is within 60 feet of a symbolic representation of one. Otherwise, Endelyn disappears in a cloud of inky smoke when she drops to 0 hit points, along with anything she was wearing or carrying, and reappears 24 hours later in the same location or the nearest unoccupied space.

**Uncanny Awareness.** Endelyn can't be surprised.


---

### Actions

**Multiattack.** Endelyn makes two Puppeteer's Lash attacks

**Puppeteer's Lash.** Melee or Ranged Spell Attack: +6 to hit, reach 5 ft. or range 60 ft., one creature. *Hit:* 17 (4d6 + 3) psychic damage, and if the target is Large or smaller, Endelyn telekinetically moves it up to 10 feet in any direction horizontally.


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
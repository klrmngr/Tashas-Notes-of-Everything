---
type: pc
race: "Fey"
class:
 - "Sprite Skirmisher"
subClass:
 - "CR 1/4"
cover: "Sprite Skirmisher.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/tiny
  - cr/1-4
  - source/hotb
---
###### Sprite Skirmisher
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: HotB
___

> [!infobox|no-t right]
> ![[Sprite Skirmisher.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Tiny Fey |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 10 (4d4) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | HotB |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 3 | 18 | 10 | 14 | 13 | 11 |
| **Mod** | -4 | +4 | +0 | +2 | +1 | +0 |

**Speed:** 10 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Elvish, Sylvan
**Skills:** Perception +3, Stealth +8

---

### Actions

**Needle Sword.** m +6, reach 5 ft. *Hit:* 6 (1d4 + 4) Piercing damage.

**Enchanting Bow.** r +6, range 40/160 ft. *Hit:* 1 Piercing damage, and the target has the Charmed condition until the start of the sprite's next turn.

**Heart Sight.** cha DC 10, one creature within 5 feet the sprite can see (Celestials, Fiends, Undead automatically fail the save).  The sprite knows the target's emotions.

**Invisibility.** The sprite has the Invisible condition for 1 minute. This effect ends early immediately after the sprite makes an attack roll or deals damage, or if the sprite has the Incapacitated condition.


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
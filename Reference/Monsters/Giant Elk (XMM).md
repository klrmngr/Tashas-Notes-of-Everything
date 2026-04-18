---
type: pc
race: "Celestial"
class:
 - "Giant Elk"
subClass:
 - "CR 2"
cover: "Giant Elk.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/huge
  - cr/2
  - source/xmm
---
###### Giant Elk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Giant Elk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Huge Celestial |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 42 (5d12 + 10) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 18 | 14 | 7 | 14 | 10 |
| **Mod** | +4 | +4 | +2 | -2 | +2 | +0 |

**Speed:** 60 ft. &nbsp;|&nbsp; **Senses:** Darkvision 90 ft., passive Perception 14
**Languages:** Celestial; understands Common, Elvish, and Sylvan but can't speak them
**Saving Throws:** Str +6, Dex +6
**Skills:** Perception +4
**Damage Resistances:** necrotic; radiant

---

### Actions

**Ram.** m +6, reach 10 ft. *Hit:* 11 (2d6 + 4) Bludgeoning damage plus 5 (2d4) Radiant damage. If the target is a Huge or smaller creature and the elk moved 20+ feet straight toward it immediately before the hit, the target takes an extra 5 (2d4) Bludgeoning damage and has the Prone condition.


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
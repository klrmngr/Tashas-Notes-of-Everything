---
type: pc
race: "Construct"
class:
 - "Animated Object"
subClass:
 - "CR —"
cover: "Animated Object.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/tiny
  - cr/—
  - source/xphb
---
###### Animated Object
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XPHB
___

> [!infobox|no-t right]
> ![[Animated Object.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Tiny Construct |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 10 (Medium or smaller), 20 (Large), 40 (Huge) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | XPHB |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 10 | 10 | 3 | 3 | 1 |
| **Mod** | +3 | +0 | +0 | -4 | -4 | -5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Blindsight 30 ft., passive Perception 6
**Languages:** understands the languages you know

---

### Actions

**Slam.** m Bonus equals your spell attack modifier, reach 5 ft. *Hit:* Force damage equal to (summonSpellLevel - 4)d4 + 3, (summonSpellLevel - 3)d6 + 3 + your spellcasting ability modifier (Large), or (summonSpellLevel - 3)d12 + 3 + your spellcasting ability modifier (Huge).


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
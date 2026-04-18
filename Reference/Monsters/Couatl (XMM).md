---
type: pc
race: "Celestial"
class:
 - "Couatl"
subClass:
 - "CR 4"
cover: "Couatl.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/medium
  - cr/4
  - source/xmm
---
###### Couatl
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Couatl.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Celestial |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 19 |
> | :FasHeart: HP | 60 (8d8 + 24) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 20 | 17 | 18 | 20 | 18 |
| **Mod** | +3 | +5 | +3 | +4 | +5 | +4 |

**Speed:** 30 ft., fly 90 ft. &nbsp;|&nbsp; **Senses:** Truesight 120 ft., passive Perception 15
**Languages:** all; telepathy 120 ft.
**Saving Throws:** Con +5, Wis +7
**Damage Resistances:** bludgeoning; piercing; slashing
**Damage Immunities:** psychic; radiant

---

### Traits

**Shielded Mind.** The couatl's thoughts can't be read by any means, and other creatures can communicate with it telepathically only if it allows them.


---

### Actions

**Bite.** m +7, reach 5 ft. *Hit:* 11 (1d12 + 5) Piercing damage, and the target has the Poisoned condition until the end of the couatl's next turn.

**Constrict.** str DC 15, one Medium or smaller creature the couatl can see within 5 feet.  8 (1d6 + 5) Bludgeoning damage. The target has the Grappled condition (escape DC 13), and it has the Restrained condition until the grapple ends.


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
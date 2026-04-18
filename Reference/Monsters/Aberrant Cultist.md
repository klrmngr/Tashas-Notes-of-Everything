---
type: pc
race: "Humanoid"
class:
 - "Aberrant Cultist"
subClass:
 - "CR 8"
cover: "Aberrant Cultist.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/8
  - source/xmm
---
###### Aberrant Cultist
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Aberrant Cultist.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 137 (25d8 + 25) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 19 | 12 | 16 | 18 | 15 |
| **Mod** | +0 | +4 | +1 | +3 | +4 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 90 ft., passive Perception 17
**Languages:** Common, Deep Speech; telepathy 30 ft.
**Saving Throws:** Int +6, Wis +7
**Skills:** Arcana +6, Perception +7, Religion +6

---

### Actions

**Multiattack.** The cultist makes two Tentacle Lash attacks. It can replace any attack with a use of Mind Rot.

**Tentacle Lash.** m +7, reach 10 ft. *Hit:* 7 (1d6 + 4) Slashing damage plus 14 (4d6) Psychic damage. If the target is a Large or smaller creature, it has the Grappled condition (escape DC 14) from one of two tentacles, and it has the Restrained condition until the grapple ends.

**Mind Rot.** wis DC 15, one creature the cultist can see within 90 feet.  27 (6d8) Psychic damage, and the target has the Poisoned condition until the start of the cultist's next turn.  Half damage only.


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
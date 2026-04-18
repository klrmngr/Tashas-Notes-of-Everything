---
type: pc
race: "Aberration (gith)"
class:
 - "Githyanki Knight"
subClass:
 - "CR 8"
cover: "Githyanki Knight.png"
campaign:
locations:
tags:
  - race/gith
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/8
  - source/xmm
---
###### Githyanki Knight
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Githyanki Knight.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Aberration (gith) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 117 (18d8 + 36) |
> | :FasUserGroup: Race | Aberration (gith) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 15 | 14 | 14 | 15 |
| **Mod** | +3 | +2 | +2 | +2 | +2 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Gith
**Saving Throws:** Con +5, Int +5, Wis +5

---

### Actions

**Multiattack.** The githyanki makes three Silver Sword attacks. It can replace one attack with a use of Spellcasting to cast Telekinesis if available.

**Silver Sword.** m +6, reach 5 ft. *Hit:* 10 (2d6 + 3) Slashing damage plus 14 (4d6) Psychic damage. Critical *Hit:* If the target is in an astral body (as with the Astral Projection spell), the githyanki can cut the silvery cord that tethers the target to its material body instead of dealing damage.


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
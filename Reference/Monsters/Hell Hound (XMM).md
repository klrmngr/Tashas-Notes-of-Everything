---
type: pc
race: "Fiend"
class:
 - "Hell Hound"
subClass:
 - "CR 3"
cover: "Hell Hound.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/3
  - source/xmm
---
###### Hell Hound
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Hell Hound.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 58 (9d8 + 18) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 12 | 14 | 6 | 13 | 6 |
| **Mod** | +3 | +1 | +2 | -2 | +1 | -2 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 15
**Languages:** understands Infernal but can't speak
**Skills:** Perception +5
**Damage Immunities:** fire

---

### Traits

**Pack Tactics.** The hound has Advantage on an attack roll against a creature if at least one of the hound's allies is within 5 feet of the creature and the ally doesn't have the Incapacitated condition.


---

### Actions

**Multiattack.** The hound makes two Bite attacks.

**Bite.** m +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Piercing damage plus 3 (1d6) Fire damage.

**Fire Breath (Recharge 5–6).** dex DC 12, each creature in a 15-foot Cone.  17 (5d6) Fire damage.  Half damage.


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
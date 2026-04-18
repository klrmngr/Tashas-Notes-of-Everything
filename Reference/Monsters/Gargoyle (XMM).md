---
type: pc
race: "Elemental"
class:
 - "Gargoyle"
subClass:
 - "CR 2"
cover: "Gargoyle.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/medium
  - cr/2
  - source/xmm
---
###### Gargoyle
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Gargoyle.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Elemental |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 67 (9d8 + 27) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 11 | 16 | 6 | 11 | 7 |
| **Mod** | +2 | +0 | +3 | -2 | +0 | -2 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** Primordial (Terran)
**Skills:** Stealth +4
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; petrified; poisoned

---

### Traits

**Flyby.** The gargoyle doesn't provoke an Opportunity Attack when it flies out of an enemy's reach.


---

### Actions

**Multiattack.** The gargoyle makes two Claw attacks.

**Claw.** m +4, reach 5 ft. *Hit:* 7 (2d4 + 2) Slashing damage.


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
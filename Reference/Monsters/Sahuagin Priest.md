---
type: pc
race: "Fiend"
class:
 - "Sahuagin Priest"
subClass:
 - "CR 2"
cover: "Sahuagin Priest.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/2
  - source/xmm
---
###### Sahuagin Priest
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Sahuagin Priest.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 38 (7d8 + 7) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 11 | 12 | 12 | 14 | 13 |
| **Mod** | +1 | +0 | +1 | +1 | +2 | +1 |

**Speed:** 30 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 16
**Languages:** Sahuagin
**Skills:** Perception +6, Religion +3
**Damage Resistances:** acid; cold

---

### Traits

**Blood Frenzy.** The sahuagin has Advantage on attack rolls against any creature that doesn't have all its Hit Points.

**Limited Amphibiousness.** The sahuagin can breathe air and water, but it must be submerged at least once every 4 hours to avoid suffocating outside water.

**Shark Telepathy.** The sahuagin can magically control sharks within 120 feet of itself, using a special telepathy.


---

### Actions

**Multiattack.** The sahuagin makes two Spectral Jaws attacks.

**Spectral Jaws.** m,r +4, reach 5 ft. or range 120 ft. *Hit:* 11 (2d8 + 2) Force damage.


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
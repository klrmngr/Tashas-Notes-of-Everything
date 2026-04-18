---
type: pc
race: "Celestial"
class:
 - "Giant Eagle"
subClass:
 - "CR 1"
cover: "Giant Eagle.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/large
  - cr/1
  - source/xmm
---
###### Giant Eagle
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Giant Eagle.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Large Celestial |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 26 (4d10 + 4) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 17 | 13 | 8 | 14 | 10 |
| **Mod** | +3 | +3 | +1 | -1 | +2 | +0 |

**Speed:** 10 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Celestial; understands Common and Primordial (Auran) but can't speak them
**Skills:** Perception +6
**Damage Resistances:** necrotic; radiant

---

### Actions

**Multiattack.** The eagle makes two Rend attacks.

**Rend.** m +5, reach 5 ft. *Hit:* 5 (1d4 + 3) Slashing damage plus 3 (1d6) Radiant damage.


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
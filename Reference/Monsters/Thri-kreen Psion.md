---
type: pc
race: "Monstrosity"
class:
 - "Thri-kreen Psion"
subClass:
 - "CR 8"
cover: "Thri-kreen Psion.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/8
  - source/xmm
---
###### Thri-kreen Psion
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Thri-kreen Psion.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 149 (23d8 + 46) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 14 | 19 | 12 | 11 |
| **Mod** | +4 | +2 | +2 | +4 | +1 | +0 |

**Speed:** 40 ft., fly 20 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 14
**Languages:** Thri-kreen; telepathy 120 ft.
**Saving Throws:** Str +7, Dex +5, Con +5, Int +7
**Skills:** Perception +4, Stealth +8
**Damage Resistances:** psychic

---

### Actions

**Multiattack.** The thri-kreen makes three Psionic Lance attacks.

**Psionic Lance.** m,r +7, reach 10 ft. or range 120 ft. *Hit:* 18 (4d6 + 4) Psychic damage.


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
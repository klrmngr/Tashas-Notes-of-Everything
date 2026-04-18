---
type: pc
race: "Elemental"
class:
 - "Aarakocra Aeromancer"
subClass:
 - "CR 4"
cover: "Aarakocra Aeromancer.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/medium
  - cr/4
  - source/xmm
---
###### Aarakocra Aeromancer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Aarakocra Aeromancer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Elemental |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 66 (12d8 + 12) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 12 | 13 | 17 | 12 |
| **Mod** | +0 | +3 | +1 | +1 | +3 | +1 |

**Speed:** 20 ft., fly 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 17
**Languages:** Aarakocra, Primordial (Auran)
**Saving Throws:** Dex +5, Wis +5
**Skills:** Arcana +3, Nature +5, Perception +7

---

### Actions

**Multiattack.** The aarakocra makes two Wind Staff attacks, and it can use Spellcasting to cast Gust of Wind.

**Wind Staff.** m,r +5, reach 5 ft. or range 120 ft. *Hit:* 7 (1d8 + 3) Bludgeoning damage plus 11 (2d10) Lightning damage.


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
---
type: pc
race: "Humanoid (wizard)"
class:
 - "Archmage"
subClass:
 - "CR 12"
cover: "Archmage.png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/12
  - source/xmm
---
###### Archmage
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Archmage.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Small Humanoid (wizard) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 170 (31d8 + 31) |
> | :FasUserGroup: Race | Humanoid (wizard) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 12 | 20 | 15 | 16 |
| **Mod** | +0 | +2 | +1 | +5 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common plus five other languages
**Saving Throws:** Int +9, Wis +6
**Skills:** Arcana +13, History +9, Perception +6
**Damage Immunities:** psychic
**Condition Immunities:** (with Mind Blank)

---

### Traits

**Magic Resistance.** The archmage has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The archmage makes four Arcane Burst attacks.

**Arcane Burst.** m,r +9, reach 5 ft. or range 150 ft. *Hit:* 27 (4d10 + 5) Force damage.


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
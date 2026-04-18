---
type: pc
race: "Elemental"
class:
 - "Azer Pyromancer"
subClass:
 - "CR 6"
cover: "Azer Pyromancer.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/medium
  - cr/6
  - source/xmm
---
###### Azer Pyromancer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Azer Pyromancer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Elemental |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 97 (13d8 + 39) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 14 | 16 | 12 | 18 | 13 |
| **Mod** | +2 | +2 | +3 | +1 | +4 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 17
**Languages:** Primordial (Ignan)
**Saving Throws:** Con +6, Wis +7
**Skills:** Arcana +4, Perception +7
**Damage Immunities:** fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Fire Aura.** At the end of each of the azer's turns, each creature of the azer's choice in a 5-foot Emanation originating from the azer takes 11 (2d10) Fire damage unless the azer has the Incapacitated condition.

**Illumination.** The azer sheds Bright Light in a 10-foot radius and Dim Light for an additional 10 feet.


---

### Actions

**Multiattack.** The azer makes two Flame Burst attacks.

**Flame Burst.** m,r +7, reach 5 ft. or range 120 ft. *Hit:* 15 (2d10 + 4) Fire damage.


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
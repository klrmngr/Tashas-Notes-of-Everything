---
type: pc
race: "Humanoid (elf)"
class:
 - "Umbragen Shadow Walker"
subClass:
 - "CR 9"
cover: "Umbragen Shadow Walker.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/efa
---
###### Umbragen Shadow Walker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: EFA
___

> [!infobox|no-t right]
> ![[Umbragen Shadow Walker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 162 (25d8 + 50) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | EFA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 19 | 14 | 13 | 15 | 20 |
| **Mod** | +1 | +4 | +2 | +1 | +2 | +5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 16
**Languages:** Common, Elvish, Undercommon
**Saving Throws:** Dex +8, Wis +6
**Skills:** Arcana +5, Perception +6, Stealth +8
**Damage Vulnerabilities:** radiant

---

### Traits

**Fey Ancestry.** Magic can't put the shadow walker to sleep.

**Sunlight Sensitivity.** While in sunlight, the shadow walker has Disadvantage on ability checks and attack rolls.


---

### Actions

**Multiattack.** The shadow walker makes three Gloom Burst attacks and uses Shadow Cowl.

**Gloom Burst.** m,r +9, reach 5 ft. or range 120 ft. *Hit:* 14 (2d8 + 5) Psychic damage.

**Shadow Cowl.** wis DC 17, one creature the shadow walker can see within 120 feet.  14 (4d6) Necrotic damage, and the target has the  Blinded condition until the start of the shadow walker's next turn.


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
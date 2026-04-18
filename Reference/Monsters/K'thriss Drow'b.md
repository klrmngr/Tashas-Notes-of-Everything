---
type: pc
race: "Humanoid (elf)"
class:
 - "K'thriss Drow'b"
subClass:
 - "CR 3"
cover: "K'thriss Drow'b.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/ai
---
###### K'thriss Drow'b
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Acquisitions Incorporated
___

> [!infobox|no-t right]
> ![[K'thriss Drow'b.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 14 (studded leather) |
> | :FasHeart: HP | 44 (8d8 + 8) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | Acquisitions Incorporated |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 14 | 12 | 14 | 11 | 18 |
| **Mod** | -1 | +2 | +1 | +2 | +0 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 12
**Languages:** Celestial, Common, Elvish, Undercommon; can read all writing
**Saving Throws:** Str +0, Dex +3, Con +2, Int +3, Wis +3, Cha +7
**Skills:** Arcana +4, Insight +2, Investigation +4, Perception +2, Religion +4

---

### Traits

**Special Equipment.** K'thriss wears a robe of stars (accounted for in his statistics). The robe allows him to cast the following spells: 6/day: magic missile (7 missiles)

**Awakened Mind.** K'thriss can telepathically speak to any creature he can see within 30 feet of him, provided the creature can understand at least one language.

**Fey Ancestry.** K'thriss has advantage on saving throws against being charmed, and magic can't put him to sleep. Sunlight Sensitivity. While in sunlight, K'thriss has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** K'thriss makes two attacks with his sickle.

**Sickle.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) slashing damage.


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
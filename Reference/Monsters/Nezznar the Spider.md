---
type: pc
race: "Humanoid (elf, wizard)"
class:
 - "Nezznar the Spider"
subClass:
 - "CR 2"
cover: "Nezznar the Spider.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/pabtso
---
###### Nezznar the Spider
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Phandelver and Below: The Shattered Obelisk
___

> [!infobox|no-t right]
> ![[Nezznar the Spider.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf, wizard) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 11; 14 with mage armor |
> | :FasHeart: HP | 27 (6d8) |
> | :FasUserGroup: Race | Humanoid (elf, wizard) |
> | :FasBook: Source | Phandelver and Below: The Shattered Obelisk |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 13 | 10 | 16 | 14 | 13 |
| **Mod** | -1 | +1 | +0 | +3 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 14
**Languages:** Common, Elvish, Undercommon
**Saving Throws:** Int +5, Wis +4
**Skills:** Arcana +5, Perception +4, Stealth +3

---

### Traits

**Special Equipment.** Nezznar has a fully charged spider staff (see appendix B).

**Fey Ancestry.** Nezznar has advantage on saving throws to avoid or end the charmed condition on himself, and magic can't put him to sleep.

**Sunlight Sensitivity.** Nezznar has disadvantage on attack rolls while he or his target is in sunlight.


---

### Actions

**Multiattack.** Nezznar makes two Poison Blast attacks.

**Poison Blast.** Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 120 ft., one creature. *Hit:* 9 (2d8) poison damage.


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
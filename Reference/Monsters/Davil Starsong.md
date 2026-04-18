---
type: pc
race: "Humanoid (elf)"
class:
 - "Davil Starsong"
subClass:
 - "CR 6"
cover: "Davil Starsong.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/6
  - source/wdh
---
###### Davil Starsong
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Davil Starsong.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 (chain shirt) |
> | :FasHeart: HP | 82 (15d8 + 15) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 12 | 16 | 12 | 17 |
| **Mod** | +0 | +2 | +1 | +3 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Common, Draconic, Dwarvish, Elvish
**Saving Throws:** Dex +5, Cha +6
**Skills:** Arcana +6, History +6, Insight +4, Perception +4, Performance +6

---

### Traits

**Fey Ancestry.** Davil has advantage on saving throws against being charmed, and magic can't put him to sleep.


---

### Actions

**Dagger.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage. Or Ranged Weapon Attack: +5 to hit, range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.


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
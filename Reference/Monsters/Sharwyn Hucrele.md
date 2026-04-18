---
type: pc
race: "Humanoid (human)"
class:
 - "Sharwyn Hucrele"
subClass:
 - "CR 1/2"
cover: "Sharwyn Hucrele.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-2
  - source/tftyp
---
###### Sharwyn Hucrele
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tales from the Yawning Portal
___

> [!infobox|no-t right]
> ![[Sharwyn Hucrele.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 (Barkskin trait) |
> | :FasHeart: HP | 13 (2d8 + 4) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Tales from the Yawning Portal |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 13 | 14 | 16 | 14 | 9 |
| **Mod** | +0 | +1 | +2 | +3 | +2 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Draconic, Goblin
**Skills:** Arcana +5, Insight +4, Persuasion +1

---

### Traits

**Barkskin.** Sharwyn's AC can't be lower than 16.

**Special Equipment.** Sharwyn has a spellbook that contains the spells listed in her Spellcasting trait, plus detect magic and silent image.

**Tree Thrall.** If the Gulthias Tree dies, Sharwyn dies 24 hours later.


---

### Actions

**Dagger.** Melee Weapon Attack: +4, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.


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
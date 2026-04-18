---
type: pc
race: "Humanoid (half-elf)"
class:
 - "Talis the White"
subClass:
 - "CR 5"
cover: "Talis the White.png"
campaign:
locations:
tags:
  - race/half-elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/hotdq
---
###### Talis the White
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Hoard of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Talis the White.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (half-elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (+1 scale mail, shield) |
> | :FasHeart: HP | 58 (9d8 + 18) |
> | :FasUserGroup: Race | Humanoid (half-elf) |
> | :FasBook: Source | Hoard of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 12 | 14 | 10 | 16 | 16 |
| **Mod** | +2 | +1 | +2 | +0 | +3 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 16
**Languages:** Common, Draconic, Elvish, Infernal
**Saving Throws:** Wis +6, Cha +6
**Skills:** Deception +6, Insight +6, Perception +6, Persuasion +6

---

### Traits

**Special Equipment.** Talis has +1 scale mail and a wand of winter.

**Fey Ancestry.** Talis has advantage on saving throws against being charmed, and magic can't put her to sleep.

**Winter Strike (3/Day).** Once per turn, when Talis hits with a melee attack, she can expend a use of this trait to deal an extra 9 (2d8) cold damage.


---

### Actions

**Spear.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or ranged 20/60 ft., one target. *Hit:* 6 (1d6 + 2) piercing damage.


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
---
type: pc
race: "Humanoid"
class:
 - "Astral Elf Commander"
subClass:
 - "CR 7"
cover: "Astral Elf Commander.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/7
  - source/bam
---
###### Astral Elf Commander
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Astral Elf Commander.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 17 (half plate) |
> | :FasHeart: HP | 143 (26d8 + 26) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 15 | 13 | 18 | 18 | 18 |
| **Mod** | +1 | +2 | +1 | +4 | +4 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Celestial, Common, Elvish
**Saving Throws:** Dex +5, Con +4, Wis +7, Cha +7
**Skills:** Deception +7, History +7, Intimidation +7, Survival +7

---

### Traits

**Fey Ancestry.** The elf has advantage on saving throws it makes to avoid or end the charmed condition on itself, and magic can't put it to sleep.

**Unusual Nature.** The elf doesn't require sleep.


---

### Actions

**Multiattack.** The elf makes two Longsword or Longbow attacks.

**Longsword.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d8 + 1) slashing damage, or 6 (1d10 + 1) slashing damage when used with two hands, plus 14 (4d6) radiant damage.

**Longbow.** Ranged Weapon Attack: +5 to hit, range 150/600 ft., one target. *Hit:* 6 (1d8 + 2) piercing damage plus 14 (4d6) radiant damage.


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
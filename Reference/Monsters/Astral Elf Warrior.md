---
type: pc
race: "Humanoid"
class:
 - "Astral Elf Warrior"
subClass:
 - "CR 3"
cover: "Astral Elf Warrior.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/bam
---
###### Astral Elf Warrior
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Astral Elf Warrior.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (breastplate) |
> | :FasHeart: HP | 58 (13d8) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 15 | 10 | 16 | 16 | 15 |
| **Mod** | +1 | +2 | +0 | +3 | +3 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Celestial, Common, Elvish
**Saving Throws:** Dex +4, Wis +5
**Skills:** Intimidation +4, Survival +5

---

### Traits

**Fey Ancestry.** The elf has advantage on saving throws it makes to avoid or end the charmed condition on itself, and magic can't put it to sleep.

**Unusual Nature.** The elf doesn't require sleep.


---

### Actions

**Multiattack.** The elf makes two Longsword or Longbow attacks.

**Longsword.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 5 (1d8 + 1) slashing damage, or 6 (1d10 + 1) slashing damage when used with two hands, plus 10 (3d6) radiant damage.

**Longbow.** Ranged Weapon Attack: +4 to hit, range 150/600 ft., one target. *Hit:* 6 (1d8 + 2) piercing damage plus 10 (3d6) radiant damage.


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
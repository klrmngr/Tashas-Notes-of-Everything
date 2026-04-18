---
type: pc
race: "Humanoid"
class:
 - "Astral Elf Honor Guard"
subClass:
 - "CR 5"
cover: "Astral Elf Honor Guard.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/bam
---
###### Astral Elf Honor Guard
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Astral Elf Honor Guard.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 17 (half plate) |
> | :FasHeart: HP | 93 (17d8 + 17) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 15 | 12 | 17 | 16 | 16 |
| **Mod** | +2 | +2 | +1 | +3 | +3 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 16
**Languages:** Celestial, Common, Elvish
**Saving Throws:** Wis +6, Cha +6
**Skills:** Intimidation +6, Perception +6, Survival +6

---

### Traits

**Fey Ancestry.** The elf has advantage on saving throws it makes to avoid or end the charmed condition on itself, and magic can't put it to sleep.

**Unusual Nature.** The elf doesn't require sleep.


---

### Actions

**Multiattack.** The elf makes two Longsword or Radiant Ray attacks.

**Longsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 11 (2d8 + 2) slashing damage, or 13 (2d10 + 2) slashing damage when used with two hands, plus 10 (3d6) radiant damage.

**Radiant Ray.** Ranged Spell Attack: +6 to hit, range 120 ft., one target. *Hit:* 22 (4d10) radiant damage.


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
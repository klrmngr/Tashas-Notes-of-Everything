---
type: pc
race: "Humanoid (bard)"
class:
 - "Silverquill Apprentice"
subClass:
 - "CR 2"
cover: "Silverquill Apprentice.png"
campaign:
locations:
tags:
  - race/bard
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/2
  - source/scc
---
###### Silverquill Apprentice
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Silverquill Apprentice.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Humanoid (bard) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 44 (8d8 + 8) |
> | :FasUserGroup: Race | Humanoid (bard) |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 13 | 12 | 11 | 15 |
| **Mod** | +0 | +2 | +1 | +1 | +0 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common plus any two languages
**Saving Throws:** Dex +4, Cha +4
**Skills:** Deception +4, Performance +6, Persuasion +6

---

### Actions

**Ink Blade.** Melee or Ranged Spell Attack: +4 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage plus 9 (2d8) psychic damage.


---

### Reactions

**Rousing Verse.** When a creature the apprentice can see within 30 feet of it fails a saving throw, the apprentice magically weaves together stirring prose, allowing the creature to reroll the saving throw and use the higher result.


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
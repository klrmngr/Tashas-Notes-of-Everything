---
type: pc
race: "Humanoid (bard)"
class:
 - "Silverquill Pledgemage"
subClass:
 - "CR 4"
cover: "Silverquill Pledgemage.png"
campaign:
locations:
tags:
  - race/bard
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/4
  - source/scc
---
###### Silverquill Pledgemage
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Silverquill Pledgemage.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Small Humanoid (bard) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 66 (12d8 + 12) |
> | :FasUserGroup: Race | Humanoid (bard) |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 13 | 12 | 11 | 17 |
| **Mod** | +0 | +3 | +1 | +1 | +0 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common plus any two languages
**Saving Throws:** Dex +5, Wis +2, Cha +5
**Skills:** Deception +5, Performance +7, Persuasion +7

---

### Actions

**Ink Blade.** Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 5 (1d8 + 3) piercing damage plus 10 (3d6) psychic damage.


---

### Bonus Actions

**Demotivate (2/Day).** The pledgemage hurls magical insults at one creature it can see within 30 feet of itself. The target must succeed on a DC 13 Wisdom saving throw or become frightened of the pledgemage for 1 minute. While frightened in this way, the target can't take reactions, its speed is halved, and any hit the pledgemage scores against the creature is a critical hit. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


---

### Reactions

**Rousing Verse.** When a creature the pledgemage can see within 30 feet of it fails a saving throw, the pledgemage magically weaves together stirring prose, allowing the creature to reroll the saving throw and use the higher result.


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
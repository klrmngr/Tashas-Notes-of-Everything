---
type: pc
race: "Humanoid (warlock)"
class:
 - "Oriq Recruiter"
subClass:
 - "CR 4"
cover: "Oriq Recruiter.png"
campaign:
locations:
tags:
  - race/warlock
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/4
  - source/scc
---
###### Oriq Recruiter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Oriq Recruiter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (warlock) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 (misdirecting defense) |
> | :FasHeart: HP | 55 (10d8 + 10) |
> | :FasUserGroup: Race | Humanoid (warlock) |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 12 | 17 | 15 | 18 |
| **Mod** | +0 | +2 | +1 | +3 | +2 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common plus any two languages
**Saving Throws:** Int +5, Wis +4, Cha +6
**Skills:** Arcana +5, Deception +8, Insight +4, Persuasion +6
**Damage Resistances:** psychic
**Condition Immunities:** charmed; frightened

---

### Traits

**Misdirecting Defense.** The AC of the recruiter includes its Charisma modifier while it isn't wearing armor or wielding a shield.

**Oriq Mask.** The recruiter wears an Oriq mask. While wearing the mask, the recruiter can't be targeted by any divination magic or perceived through magical scrying sensors, and it adds double its proficiency bonus to Charisma (Deception) checks (included above).


---

### Actions

**Multiattack.** The recruiter makes two Psychic Knife attacks. It can use Spellcasting in place of one of the attacks.

**Psychic Knife.** Melee or Ranged Spell Attack: +6 to hit, reach 5 ft. or range 30 ft., one creature. *Hit:* 21 (5d6 + 4) psychic damage.


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
---
type: pc
race: "Humanoid (wizard)"
class:
 - "Quandrix Professor of Theory"
subClass:
 - "CR 7"
cover: "Quandrix Professor of Theory.png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/7
  - source/scc
---
###### Quandrix Professor of Theory
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Quandrix Professor of Theory.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Small Humanoid (wizard) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 97 (15d8 + 30) |
> | :FasUserGroup: Race | Humanoid (wizard) |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 14 | 14 | 19 | 15 | 13 |
| **Mod** | +0 | +2 | +2 | +4 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common plus any four languages
**Saving Throws:** Con +5, Int +7, Wis +5, Cha +4
**Skills:** Arcana +10, Insight +5, Investigation +10, Perception +5
**Damage Resistances:** psychic
**Condition Immunities:** charmed; frightened

---

### Actions

**Multiattack.** The professor makes two Heuristic Lance attacks. It can also use Overriding Theorem, if available.

**Heuristic Lance.** Melee or Ranged Spell Attack: +7 to hit, reach 5 ft. or range 60 ft., one creature. *Hit:* 13 (2d8 + 4) psychic damage, and the target is poisoned until the end of its next turn.

**Overriding Theorem (Recharge 4–6).** The professor magically influences the mind of up to two creatures it can see within 60 feet of itself. Each target must succeed on a DC 15 Intelligence saving throw or become charmed by the professor until the start of the professor's next turn. The charmed creature must immediately use its reaction, if available, to move up its speed toward another creature of the professor's choice and make one melee attack against that other creature.


---

### Reactions

**Divide by Zero (2/Day).** When the professor sees another creature within 60 feet of itself casting a spell, the professor can try to nullify the spell's formation. The creature must succeed on a DC 15 saving throw using the spell's spellcasting ability, or the spell fails and is wasted.


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
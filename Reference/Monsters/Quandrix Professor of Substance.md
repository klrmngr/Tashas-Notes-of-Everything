---
type: pc
race: "Humanoid (wizard)"
class:
 - "Quandrix Professor of Substance"
subClass:
 - "CR 7"
cover: "Quandrix Professor of Substance.png"
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
###### Quandrix Professor of Substance
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Quandrix Professor of Substance.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Small Humanoid (wizard) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 104 (16d8 + 32) |
> | :FasUserGroup: Race | Humanoid (wizard) |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 14 | 14 | 19 | 14 | 13 |
| **Mod** | +0 | +2 | +2 | +4 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common plus any four languages
**Saving Throws:** Con +5, Int +7, Wis +5, Cha +4
**Skills:** Arcana +10, Investigation +10, Nature +7, Perception +5
**Damage Resistances:** force

---

### Actions

**Multiattack.** The professor makes two Spatial Blade attacks.

**Spatial Blade.** Melee or Ranged Spell Attack: +7 to hit (the target can't benefit from cover less than 3), reach 5 ft. or range 120 ft., one target. *Hit:* 13 (2d8 + 4) force damage, or 22 (4d8 + 4) force damage if the professor is Large or larger, and the professor can push the target horizontally up to 10 feet away.


---

### Bonus Actions

**Dilation (Recharge 5–6).** The professor magically alters its physical form until it uses this bonus action again, until it is incapacitated or dies, or until it dismisses the effect (no action required). Choose one of the following options:

**Expand.** The professor becomes Large if there is sufficient room for it to grow. It has advantage on attack rolls and on ability checks and saving throws that rely on Strength.

**Contract.** The professor becomes Small. Its walking speed increases to 60 feet, attack rolls against it have disadvantage, and it has advantage on ability checks and saving throws that rely on Dexterity.


---

### Reactions

**Avoidant Translation (2/Day).** When the professor is hit by an attack roll, it can increase its AC by 3 against that attack, potentially causing it to miss. The professor can then teleport, along with any equipment it is wearing or carrying, up to 30 feet to an unoccupied space it can see.


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
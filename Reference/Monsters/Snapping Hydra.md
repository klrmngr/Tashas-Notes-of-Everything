---
type: pc
race: "Monstrosity"
class:
 - "Snapping Hydra"
subClass:
 - "CR 11"
cover: "Snapping Hydra.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/huge
  - cr/11
  - source/mcv4ec
---
###### Snapping Hydra
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV4EC
___

> [!infobox|no-t right]
> ![[Snapping Hydra.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Huge Monstrosity |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 149 (13d12 + 65) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | MCV4EC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 5 | 21 | 2 | 16 | 7 |
| **Mod** | +5 | -3 | +5 | -4 | +3 | -2 |

**Speed:** 30 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 21
**Languages:** —
**Skills:** Perception +11
**Condition Immunities:** blinded; charmed; deafened; frightened; stunned; unconscious

---

### Traits

**Amphibious.** The hydra can breathe air and water.

**Multiple Heads.** The hydra has five heads. Whenever the hydra takes 30 or more damage in a single turn, one of its heads dies. If all its heads die, the hydra dies.
At the end of its turn, the hydra grows two heads for each of its heads that died since its last turn, unless it has taken cold damage since its last turn. The hydra regains 10 hit points for each head regrown this way.

**Reactive Heads.** For each head the hydra has beyond one, it gets an extra reaction that can be used only for opportunity attacks.

**Wakeful.** While the hydra sleeps, at least one of its heads is awake.


---

### Actions

**Multiattack.** The hydra makes as many Bite attacks as it has heads.

**Bite.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 14 (2d8 + 5) piercing damage.

**Shell Defense.** The hydra withdraws its limbs and heads into its shell. Until it emerges as a bonus action, it gains a +4 bonus to AC and has advantage on Strength and Constitution saving throws. While in its shell, the hydra has the prone condition, its speed is 0 and can't increase, its heads can't die, it has disadvantage on Dexterity saving throws, and it can't take any other actions or reactions.


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
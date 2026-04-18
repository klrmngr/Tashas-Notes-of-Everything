---
type: pc
race: "Fey"
class:
 - "Goose Mother"
subClass:
 - "CR 7"
cover: "Goose Mother.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/huge
  - cr/7
  - source/mcv4ec
---
###### Goose Mother
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV4EC
___

> [!infobox|no-t right]
> ![[Goose Mother.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Huge Fey |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 114 (12d12 + 36) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | MCV4EC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 15 | 17 | 12 | 18 | 15 |
| **Mod** | +3 | +2 | +3 | +1 | +4 | +2 |

**Speed:** 40 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 20
**Languages:** —
**Saving Throws:** Str +6, Int +4
**Skills:** Insight +7, Investigation +4, Perception +10
**Condition Immunities:** blinded; charmed; deafened; frightened; stunned; unconscious

---

### Traits

**Legendary Resistance (3/Day).** If the Goose Mother fails a saving throw, it can choose to succeed instead.

**Multiple Heads.** The Goose Mother has five heads. Whenever the Goose Mother takes 25 or more damage in a single turn, one of its heads dies. If all its heads die, the Goose Mother dies.
At the end of its turn, the Goose Mother grows two heads for each of its heads that died since its last turn, unless it has taken poison damage since its last turn. The Goose Mother regains 10 hit points for each head when it regrows.

**Reactive Heads.** For each head the Goose Mother has beyond one, it gets an extra reaction that can be used only for opportunity attacks.

**Wakeful.** While the Goose Mother sleeps, at least one of its heads is awake.


---

### Actions

**Multiattack.** The Goose Mother makes as many Beak attacks as it has heads and one Wing attack.

**Beak.** Melee Weapon Attack: +6 to hit, reach 10 ft., one target. *Hit:* 6 (1d6 + 3) bludgeoning damage.

**Wing.** Melee Weapon Attack: +6 to hit, reach 10 ft., one target. *Hit:* 9 (1d12 + 3) bludgeoning damage. If the target is a Large or smaller creature, it must succeed on a DC 15 Strength saving throw or have the prone condition.

**Lullaby of Honks (Recharge 5–6).** The Goose Mother's heads honk a discordant lullaby. Each creature of the Goose Mother's choice within 10 feet of it must make a DC 15 Constitution saving throw. On a failed save, a creature takes 7 (2d6) thunder damage and falls into a magical slumber. On a successful save, the target takes half as much damage only. The honks can be heard up to 300 feet away.
A creature under magical slumber has the unconscious condition for 8 hours. This effect ends early for a creature if it takes damage or another creature uses an action to shake it awake.


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
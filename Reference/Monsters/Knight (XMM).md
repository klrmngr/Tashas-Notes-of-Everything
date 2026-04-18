---
type: pc
race: "Humanoid"
class:
 - "Knight"
subClass:
 - "CR 3"
cover: "Knight.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/3
  - source/xmm
---
###### Knight
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Knight.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 52 (8d8 + 16) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 11 | 14 | 11 | 11 | 15 |
| **Mod** | +3 | +0 | +2 | +0 | +0 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common plus one other language
**Saving Throws:** Con +4, Wis +2
**Condition Immunities:** frightened

---

### Actions

**Multiattack.** The knight makes two attacks, using Greatsword or Heavy Crossbow in any combination.

**Greatsword.** m +5, reach 5 ft. *Hit:* 10 (2d6 + 3) Slashing damage plus 4 (1d8) Radiant damage.

**Heavy Crossbow.** r +2, range 100/400 ft. *Hit:* 11 (2d10) Piercing damage plus 4 (1d8) Radiant damage.


---

### Reactions

**Parry.**  The knight is hit by a melee attack roll while holding a weapon.  The knight adds 2 to its AC against that attack, possibly causing it to miss.


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
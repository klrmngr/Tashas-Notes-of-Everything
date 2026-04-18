---
type: pc
race: "Humanoid"
class:
 - "Sir Jared"
subClass:
 - "CR 5"
cover: "Sir Jared.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/bmt
---
###### Sir Jared
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Sir Jared.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 20 (plate armor, shield) |
> | :FasHeart: HP | 90 (12d8 + 36) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 12 | 17 | 13 | 14 | 17 |
| **Mod** | +4 | +1 | +3 | +1 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Halfling
**Saving Throws:** Str +7, Con +6
**Skills:** Arcana +4, Athletics +7, Persuasion +6, Survival +5
**Condition Immunities:** blinded; charmed; frightened

---

### Actions

**Multiattack.** Jared makes three Longsword attacks.

**Longsword.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage plus 4 (1d8) radiant damage. On a roll of 19 or 20, Jared scores a critical hit.


---

### Reactions

**Protect Ally.** When a creature Jared can see attacks a target other than Jared that is within 5 feet of him, Jared imposes disadvantage on the attack roll.


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
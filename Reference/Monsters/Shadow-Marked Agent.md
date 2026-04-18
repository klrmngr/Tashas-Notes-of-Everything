---
type: pc
race: "Humanoid (elf)"
class:
 - "Shadow-Marked Agent"
subClass:
 - "CR 7"
cover: "Shadow-Marked Agent.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/7
  - source/efa
---
###### Shadow-Marked Agent
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: EFA
___

> [!infobox|no-t right]
> ![[Shadow-Marked Agent.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 132 (24d8 + 24) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | EFA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 20 | 12 | 11 | 16 | 17 |
| **Mod** | +1 | +5 | +1 | +0 | +3 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 16
**Languages:** Common, Elvish, Thieves' cant
**Saving Throws:** Dex +8, Wis +6
**Skills:** Perception +6, Performance +6, Sleight Of Hand +8, Stealth +11

---

### Actions

**Multiattack.** The agent makes two Shadow Knife attacks.

**Shadow Knife.** m,r +8, reach 5 ft. or range 20/60 ft. *Hit:* 10 (2d4 + 5) Piercing damage plus 14 (4d6) Necrotic damage, and the target's Speed is reduced by 10 feet until the end of its next turn.


---

### Bonus Actions

**Shadow Cloak.** The agent has the Invisible condition until the start of its next turn. This invisibility ends early immediately after the agent makes an attack roll.


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
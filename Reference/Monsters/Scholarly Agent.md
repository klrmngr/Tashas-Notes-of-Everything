---
type: pc
race: "Humanoid (wizard)"
class:
 - "Scholarly Agent"
subClass:
 - "CR 1"
cover: "Scholarly Agent.png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1
  - source/crcotn
---
###### Scholarly Agent
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Scholarly Agent.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Small Humanoid (wizard) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 22 (4d8 + 4) |
> | :FasUserGroup: Race | Humanoid (wizard) |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 12 | 12 | 16 | 12 | 10 |
| **Mod** | +0 | +1 | +1 | +3 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common plus one other language
**Saving Throws:** Int +5
**Skills:** Arcana +5, History +5, Investigation +5

---

### Actions

**Arcane Shock.** Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 30 ft., one target. *Hit:* 14 (2d10 + 3) lightning damage. If the target is a creature, it can't take reactions until the start of its next turn.


---

### Reactions

**Glyph of Shielding.** The agent adds 2 to its AC against one attack that would hit it. To do so, the agent must be able to see the attacker and have a free hand.


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
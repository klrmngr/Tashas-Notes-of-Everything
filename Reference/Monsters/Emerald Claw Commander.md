---
type: pc
race: "Humanoid"
class:
 - "Emerald Claw Commander"
subClass:
 - "CR 4"
cover: "Emerald Claw Commander.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/4
  - source/efa
---
###### Emerald Claw Commander
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: EFA
___

> [!infobox|no-t right]
> ![[Emerald Claw Commander.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 20 |
> | :FasHeart: HP | 78 (12d8 + 24) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | EFA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 11 | 15 | 15 | 12 | 14 |
| **Mod** | +4 | +0 | +2 | +2 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Dwarvish
**Saving Throws:** Con +4, Wis +3
**Skills:** Athletics +6, Intimidation +4, Perception +3

---

### Traits

**Aura of Authority.** While in a 30-foot Emanation originating from the commander, the commander and its allies have Advantage on attack rolls and saving throws, provided the commander doesn't have the Incapacitated condition.


---

### Actions

**Multiattack.** The commander makes two attacks, using Flail or Javelin in any combination.

**Flail.** m +6, reach 5 ft.  *Hit:* 8 (1d8 + 4) Bludgeoning damage—plus 7 (2d6) Necrotic damage if the commander is Bloodied—and the target has Disadvantage on its next attack roll before the start of the commander's next turn.

**Javelin.** m,r +6, reach 5 ft. or range 30/120 ft.  *Hit:* 7 (1d6 + 4) Piercing damage—plus 7 (2d6) Necrotic damage if the commander is Bloodied.


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
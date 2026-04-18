---
type: pc
race: "Humanoid"
class:
 - "Scholarly Excavator"
subClass:
 - "CR 3"
cover: "Scholarly Excavator.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/3
  - source/crcotn
---
###### Scholarly Excavator
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Scholarly Excavator.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (breastplate) |
> | :FasHeart: HP | 67 (9d8 + 27) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 14 | 16 | 14 | 14 | 12 |
| **Mod** | +2 | +2 | +3 | +2 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common plus two other languages
**Saving Throws:** Con +5, Int +4
**Skills:** Arcana +4, Athletics +4, History +4

---

### Traits

**Siege Expert.** The excavator deals double damage to objects and structures.


---

### Actions

**Multiattack.** The excavator makes three Thunderous Warhammer attacks.

**Thunderous Warhammer.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 7 (1d10 + 2) thunder damage.


---

### Bonus Actions

**Telekinetic Toss (Recharge 5–6).** The excavator targets one Medium or smaller creature or an object weighing 300 pounds or less that isn't being worn or carried. The target, which must be within 30 feet of the excavator and visible to it, is magically pushed up to 20 feet horizontally in a direction of the excavator's choice. If the target is a creature, it can make a DC 13 Strength saving throw to resist the effect and is not pushed on a successful save.


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
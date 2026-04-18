---
type: pc
race: "Humanoid"
class:
 - "Warrior"
subClass:
 - "CR —"
cover: "Warrior.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/—
  - source/esk
---
###### Warrior
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: ESK
___

> [!infobox|no-t right]
> ![[Warrior.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 16 (chain shirt, shield) |
> | :FasHeart: HP | 13 (2d8 + 4) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | ESK |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 13 | 14 | 10 | 12 | 10 |
| **Mod** | +2 | +1 | +2 | +0 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, plus one of your choice
**Saving Throws:** Con +4
**Skills:** Athletics +4, Perception +3, Survival +3

---

### Traits

**Martial Role.** The warrior has one of the following traits of your choice:
- **Attacker.** The warrior gains a +2 bonus to attack rolls.
- **Defender.** The warrior gains the Protection reaction below.


---

### Actions

**Longsword.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) slashing damage, or 7 (1d10 + 2) slashing damage if used with two hands.

**Longbow.** Ranged Weapon Attack: +3 to hit, range 150/600 ft., one target. *Hit:* 5 (1d8 + 1) piercing damage.


---

### Reactions

**Protection (Defender Only).** The warrior imposes disadvantage on the attack roll of a creature within 5 feet of it whose target isn't the warrior. The warrior must be able to see the attacker.


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
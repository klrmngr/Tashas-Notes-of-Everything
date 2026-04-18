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
  - source/slw
---
###### Warrior
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: SLW
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
> | :FasShield: AC | 20 (plate armor, shield) |
> | :FasHeart: HP | 52 (8d8 + 16) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | SLW |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 14 | 10 | 12 | 10 |
| **Mod** | +3 | +2 | +2 | +0 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Common, plus one of your choice
**Saving Throws:** Con +5
**Skills:** Athletics +6, Perception +4, Survival +4

---

### Traits

**Battle Readiness.** The warrior has advantage on initiative rolls.

**Improved Critical.** The warrior's attack rolls score a critical hit on a roll of 19 or 20 on the d20.

**Martial Role.** The warrior has one of the following traits of your choice:
- **Attacker.** The warrior gains a +2 bonus to attack rolls.
- **Defender.** The warrior gains the Protection reaction below.


---

### Actions

**Extra Attack.** The warrior can attack twice, instead of once, whenever it takes the Attack action on its turn.

**Longsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands.

**Longbow.** Ranged Weapon Attack: +5 to hit, range 150/600 ft., one target. *Hit:* 6 (1d8 + 2) piercing damage.


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
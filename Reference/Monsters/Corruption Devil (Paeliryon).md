---
type: pc
race: "Fiend (devil)"
class:
 - "Corruption Devil (Paeliryon)"
subClass:
 - "CR 14"
cover: "Corruption Devil (Paeliryon).png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/14
  - source/coa
---
###### Corruption Devil (Paeliryon)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Corruption Devil (Paeliryon).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Large Fiend (devil) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 218 (19d10 + 114) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 14 | 22 | 19 | 15 | 14 |
| **Mod** | +5 | +2 | +6 | +4 | +2 | +2 |

**Speed:** 20 ft., burrow 20 ft., fly 60 ft. ((hover)) &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 120 ft., passive Perception 12
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Con +11, Wis +7
**Skills:** Arcana +9, Deception +7, Insight +7, Intimidation +7
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** poisoned; stunned

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede the paeliryon's darkvision.

**Keen Eyes.** The paeliryon scores a critical hit on a roll of 19 or 20.

**Magic Resistance.** The paeliryon has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The paeliryon makes three Claw attacks. It can replace one of the attacks with Draining Grasp (if available).

**Claw.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 16 (2d10 + 5) slashing damage plus 10 (3d6) fire damage.

**Draining Grasp (Recharge 4–6).** The paeliryon makes a Claw attack. On a hit, the target's Charisma score is reduced by 2 (1d4). This reduction lasts until the target finishes a short or long rest. A creature whose Charisma is reduced to 3 or less because of this ability, has the stunned condition for 1 minute.


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
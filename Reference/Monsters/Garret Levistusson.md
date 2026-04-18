---
type: pc
race: "Humanoid"
class:
 - "Garret Levistusson"
subClass:
 - "CR 2"
cover: "Garret Levistusson.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/llk
---
###### Garret Levistusson
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Lost Laboratory of Kwalish
___

> [!infobox|no-t right]
> ![[Garret Levistusson.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 44 (8d8 + 8) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Lost Laboratory of Kwalish |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 14 | 12 | 11 | 12 | 17 |
| **Mod** | +0 | +2 | +1 | +0 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Abyssal, Common, Infernal, Thieves' cant
**Skills:** Deception +7, Investigation +4, Performance +5, Persuasion +5

---

### Traits

**Special Equipment.** Garret wears a Ring of Warmth (included in his statistics) and wields a Gambler's Blade longsword.

**Bardic Inspiration (3/Day).** As a bonus action, Garret can give one chosen creature (other than him) a d6 inspiration die. The chosen creature must be within 60 feet of Garret and able to hear him. Once within the next 10 minutes, the creature can roll the die and add the number rolled to one ability check, attack roll, or saving throw it makes. The creature can use the inspiration die after the roll is made but before the DM says whether it succeeds or fails. Once the inspiration die is rolled, it is lost. A creature can have only one inspiration die at a time.

**Cunning Action.** On each of his turns, Garret can use a bonus action to take the Dash, Disengage, or Hide action.

**Sneak Attack (1/Turn).** Garret deals an extra 7 (2d6) damage when he hits a target with a weapon attack and has advantage on the attack roll, or when the target is within 5 feet of an ally of Garret that isn't incapacitated and Garret doesn't have disadvantage on the attack roll.


---

### Actions

**Shortsword.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.


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
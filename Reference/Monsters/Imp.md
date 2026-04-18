---
type: pc
race: "Fiend (devil)"
class:
 - "Imp"
subClass:
 - "CR 1"
cover: "Imp.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/tiny
  - cr/1
  - source/mm
---
###### Imp
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Imp.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Tiny Fiend (devil) |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 10 (3d4 + 3) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 17 | 13 | 11 | 12 | 14 |
| **Mod** | -2 | +3 | +1 | +0 | +1 | +2 |

**Speed:** 20 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 11
**Languages:** Infernal, Common
**Skills:** Deception +4, Insight +3, Persuasion +4, Stealth +5
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks not made with silvered weapons
**Damage Immunities:** fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Shapechanger.** The imp can use its action to polymorph into a beast form that resembles a rat (speed 20 ft.), a raven (20 ft., fly 60 ft.), or a spider (20 ft., climb 20 ft.), or back into its true form. Its statistics are the same in each form, except for the speed changes noted. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies.

**Devil's Sight.** Magical darkness doesn't impede the imp's darkvision.

**Magic Resistance.** The imp has advantage on saving throws against spells and other magical effects.


---

### Actions

**Sting (Bite in Beast Form).** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage, and the target must make a DC 11 Constitution saving throw, taking 10 (3d6) poison damage on a failed save, or half as much damage on a successful one.

**Invisibility.** The imp magically turns invisible until it attacks, or until its concentration ends (as if concentrating on a spell). Any equipment the imp wears or carries is invisible with it.


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
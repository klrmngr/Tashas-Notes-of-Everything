---
type: pc
race: "Fiend (devil)"
class:
 - "Spined Devil"
subClass:
 - "CR 2"
cover: "Spined Devil.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/small
  - cr/2
  - source/mm
---
###### Spined Devil
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Spined Devil.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Fiend (devil) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 22 (5d6 + 5) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 15 | 12 | 11 | 14 | 8 |
| **Mod** | +0 | +2 | +1 | +0 | +2 | -1 |

**Speed:** 20 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 12
**Languages:** Infernal, telepathy 120 ft.
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede the devil's darkvision.

**Flyby.** The devil doesn't provoke an opportunity attack when it flies out of an enemy's reach.

**Limited Spines.** The devil has twelve tail spines. Used spines regrow by the time the devil finishes a long rest.

**Magic Resistance.** The devil has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The devil makes two attacks: one with its bite and one with its fork or two with its tail spines.

**Bite.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 5 (2d4) slashing damage.

**Fork.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 3 (1d6) piercing damage.

**Tail Spine.** Ranged Weapon Attack: +4 to hit, range 20/80 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage plus 3 (1d6) fire damage.


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
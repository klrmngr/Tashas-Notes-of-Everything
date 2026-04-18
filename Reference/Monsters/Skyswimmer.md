---
type: pc
race: "Monstrosity"
class:
 - "Skyswimmer"
subClass:
 - "CR 13"
cover: "Skyswimmer.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/13
  - source/ggr
---
###### Skyswimmer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Skyswimmer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 216 (16d20 + 48) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 15 | 16 | 7 | 12 | 6 |
| **Mod** | +6 | +2 | +3 | -2 | +1 | -2 |

**Speed:** 10 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** —
**Saving Throws:** Con +8
**Skills:** Perception +6

---

### Traits

**Amphibious.** The skyswimmer can breathe air and water.


---

### Actions

**Multiattack.** The skyswimmer makes three attacks: one with its bite and two with its slam.

**Bite.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 22 (3d10 + 6) piercing damage. If the target is a Large or smaller creature, it must succeed on a DC 19 Dexterity saving throw or be swallowed by the skyswimmer. A swallowed creature is blinded and restrained, it has 3 against attacks and other effects outside the skyswimmer, and it takes 21 (6d6) acid damage at the start of each of the skyswimmer's turns. If the skyswimmer takes 30 damage or more on a single turn from the swallowed creature, the skyswimmer must succeed on a DC 18 Constitution saving throw at the end of that turn or regurgitate the creature, which falls prone in a space within 10 feet of the skyswimmer. If the skyswimmer dies, a swallowed creature is no longer restrained by it and can escape from the corpse by using 15 feet of movement, exiting prone.

**Slam.** Melee Weapon Attack: +11 to hit, reach 30 ft., one target. *Hit:* 19 (2d12 + 6) bludgeoning damage.


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
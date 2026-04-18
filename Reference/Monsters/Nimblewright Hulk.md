---
type: pc
race: "Construct"
class:
 - "Nimblewright Hulk"
subClass:
 - "CR 7"
cover: "Nimblewright Hulk.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/7
  - source/fraif
---
###### Nimblewright Hulk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Nimblewright Hulk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 104 (11d10 + 44) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 18 | 19 | 10 | 12 | 6 |
| **Mod** | +4 | +4 | +4 | +0 | +1 | -2 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 17
**Languages:** understands Common plus one other language but can't speak
**Saving Throws:** Str +7, Dex +7
**Skills:** Acrobatics +7, Perception +7
**Damage Immunities:** poison; psychic
**Condition Immunities:** charmed; exhaustion; paralyzed; petrified; poisoned

---

### Traits

**Evasion.** If the nimblewright is subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, it instead takes no damage if it succeeds on the save and only half damage if it fails, provided it doesn't have the Incapacitated condition.

**Magic Resistance.** The nimblewright has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The nimblewright makes four attacks, using Halting Slam or Radiant Ray in any combination.

**Halting Slam.** m +7, reach 10 ft. *Hit:* 15 (2d10 + 4) Bludgeoning damage, and the target's Speed is reduced to 0 until the end of its next turn.

**Radiant Ray.** r +7, range 60 ft. *Hit:* 14 (4d6) Radiant damage.


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
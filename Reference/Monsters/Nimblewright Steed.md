---
type: pc
race: "Construct"
class:
 - "Nimblewright Steed"
subClass:
 - "CR 2"
cover: "Nimblewright Steed.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/2
  - source/fraif
---
###### Nimblewright Steed
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Nimblewright Steed.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 47 (5d10 + 20) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 18 | 18 | 6 | 10 | 6 |
| **Mod** | +3 | +4 | +4 | -2 | +0 | -2 |

**Speed:** 60 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** understands Common plus one other language but can't speak
**Saving Throws:** Dex +6
**Damage Immunities:** poison; psychic
**Condition Immunities:** charmed; exhaustion; paralyzed; petrified; poisoned

---

### Traits

**Evasion.** If the nimblewright is subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, it instead takes no damage if it succeeds on the save and only half damage if it fails, provided it doesn't have the Incapacitated condition.


---

### Actions

**Hooves.** m +6, reach 5 ft. *Hit:* 7 (1d8 + 3) Bludgeoning damage. If the nimblewright moved at least 20 feet straight toward the target immediately before the hit, the target takes an extra 4 (1d8) Bludgeoning damage and, if it is Huge or smaller, has the Prone condition.


---

### Bonus Actions

**Nimble Movement.** The nimblewright takes the Disengage action.


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
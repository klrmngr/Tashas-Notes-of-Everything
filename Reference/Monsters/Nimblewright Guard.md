---
type: pc
race: "Construct"
class:
 - "Nimblewright Guard"
subClass:
 - "CR 3"
cover: "Nimblewright Guard.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/3
  - source/fraif
---
###### Nimblewright Guard
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Nimblewright Guard.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 67 (9d8 + 27) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 18 | 16 | 8 | 12 | 6 |
| **Mod** | +1 | +4 | +3 | -1 | +1 | -2 |

**Speed:** 60 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 13
**Languages:** understands Common plus one other language but can't speak
**Saving Throws:** Dex +6
**Skills:** Acrobatics +6, Perception +3
**Damage Immunities:** poison; psychic
**Condition Immunities:** charmed; exhaustion; paralyzed; petrified; poisoned

---

### Traits

**Evasion.** If the nimblewright is subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, it instead takes no damage if it succeeds on the save and only half damage if it fails, provided it doesn't have the Incapacitated condition.


---

### Actions

**Multiattack.** The nimblewright makes three attacks, using Scimitar or Clockwork Crossbow in any combination.

**Scimitar.** m +6, reach 5 ft. *Hit:* 7 (1d6 + 4) Slashing damage.

**Clockwork Crossbow.** r +6, range 80/320 ft. *Hit:* 8 (1d8 + 4) Piercing damage.


---

### Reactions

**Parry.**  The nimblewright is hit by a melee attack roll while holding a weapon.  The nimblewright adds 2 to its AC against that attack, potentially causing it to miss.


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
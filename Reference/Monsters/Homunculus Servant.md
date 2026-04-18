---
type: pc
race: "Construct"
class:
 - "Homunculus Servant"
subClass:
 - "CR —"
cover: "Homunculus Servant.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/tiny
  - cr/—
  - source/efa
---
###### Homunculus Servant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: EFA
___

> [!infobox|no-t right]
> ![[Homunculus Servant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Tiny Construct |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 5 + 5 per spell level (the homunculus has a number of Hit Dice [d4s] equal to the spell's level) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | EFA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 4 | 15 | 12 | 10 | 10 | 7 |
| **Mod** | -3 | +2 | +1 | +0 | +0 | -2 |

**Speed:** 20 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** telepathy 1 mile (works only with you)
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Evasion.** If the homunculus is subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, the homunculus instead takes no damage if it succeeds on the save and only half damage if it fails. It can't use this trait if it has the Incapacitated condition.

**Magic Bond.** Add the spell's level to any ability check or saving throw the homunculus makes.


---

### Actions

**Force Strike.** m,r Bonus equals your spell attack modifier, reach 5 ft. or range 30 ft. *Hit:* 1d6 + summonSpellLevel Force damage.


---

### Reactions

**Channel Magic.**  You cast a spell that has a range of touch while the homunculus is within 120 feet of you.  The homunculus delivers the spell through its touch.


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
---
type: pc
race: "Giant"
class:
 - "Nivix Cyclops"
subClass:
 - "CR 8"
cover: "Nivix Cyclops.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/large
  - cr/8
  - source/ggr
---
###### Nivix Cyclops
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Nivix Cyclops.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Giant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (half plate armor) |
> | :FasHeart: HP | 115 (10d10 + 60) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 9 | 22 | 7 | 10 | 9 |
| **Mod** | +7 | -1 | +6 | -2 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, Giant
**Saving Throws:** Con +9, Wis +3
**Damage Immunities:** poison; psychic
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Magic Resistance.** The cyclops has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The cyclops makes two slam attacks.

**Slam.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 23 (3d10 + 7) bludgeoning damage.


---

### Reactions

**Spell Vitalization.** Immediately after a creature casts a spell of 1st level or higher within 120 feet of the cyclops, the cyclops can move up to twice its speed without provoking opportunity attacks. It can then make one slam attack against a target of its choice.


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
---
type: pc
race: "Construct"
class:
 - "Flying Sword"
subClass:
 - "CR 1/4"
cover: "Flying Sword.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/small
  - cr/1-4
  - source/mm
---
###### Flying Sword
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Flying Sword.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Construct |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 17 (5d6) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 15 | 11 | 1 | 5 | 1 |
| **Mod** | +1 | +2 | +0 | -5 | -3 | -5 |

**Speed:** 0 ft., fly 50 ft. ((hover)) &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 7
**Languages:** —
**Saving Throws:** Dex +4
**Damage Immunities:** poison; psychic
**Condition Immunities:** blinded; charmed; deafened; frightened; paralyzed; petrified; poisoned

---

### Traits

**Antimagic Susceptibility.** The sword is incapacitated while in the area of an antimagic field. If targeted by dispel magic, the sword must succeed on a Constitution saving throw against the caster's spell save DC or fall unconscious for 1 minute.

**False Appearance.** While the sword remains motionless and isn't flying, it is indistinguishable from a normal sword.


---

### Actions

**Longsword.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 5 (1d8 + 1) slashing damage.


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
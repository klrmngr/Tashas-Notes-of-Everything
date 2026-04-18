---
type: pc
race: "Construct"
class:
 - "Loading Rig"
subClass:
 - "CR 1"
cover: "Loading Rig.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/1
  - source/kkw
---
###### Loading Rig
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: KKW
___

> [!infobox|no-t right]
> ![[Loading Rig.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 39 (6d10 + 6) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | KKW |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 11 | 13 | 1 | 3 | 1 |
| **Mod** | +4 | +0 | +1 | -5 | -4 | -5 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 6
**Languages:** —
**Damage Immunities:** poison; psychic
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Antimagic Susceptibility.** The rig is incapacitated while in the area of an antimagic field. If targeted by dispel magic, the rig must succeed on a Constitution saving throw against the caster's spell save DC or fall unconscious for 1 minute.

**Unstable.** If the rig takes damage, it must succeed on a DC 10 Constitution saving throw or be incapacitated with a speed of 0 until a creature activates it with a successful DC 10 Intelligence (Arcana) check made as an action.


---

### Actions

**Multiattack.** The armor makes two melee attacks.

**Slam.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) bludgeoning damage.


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
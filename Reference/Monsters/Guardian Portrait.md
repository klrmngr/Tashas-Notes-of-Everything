---
type: pc
race: "Construct"
class:
 - "Guardian Portrait"
subClass:
 - "CR 1"
cover: "Guardian Portrait.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/1
  - source/cos
---
###### Guardian Portrait
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Curse of Strahd
___

> [!infobox|no-t right]
> ![[Guardian Portrait.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 5 (natural armor) |
> | :FasHeart: HP | 22 (5d8) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Curse of Strahd |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 1 | 10 | 14 | 10 | 10 |
| **Mod** | -5 | -5 | +0 | +2 | +0 | +0 |

**Speed:** 0 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, plus up to two other languages
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Constructed Nature.** An animated object doesn't require air, food, drink, or sleep.
The magic that animates an object is dispelled when the construct drops to 0 hit points. An animated object reduced to 0 hit points becomes inanimate and is too damaged to be of much use or value to anyone.

**Antimagic Susceptibility.** The portrait is incapacitated while in the area of an antimagic field. If targeted by dispel magic, the portrait must succeed on a Constitution saving throw against the caster's spell save DC or become unconscious for 1 minute.

**False Appearance.** While the figure in the portrait remains motionless, the portrait is indistinguishable from a normal painting.


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
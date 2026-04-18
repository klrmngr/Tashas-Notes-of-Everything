---
type: pc
race: "Construct"
class:
 - "Ruidium Elephant"
subClass:
 - "CR 8"
cover: "Ruidium Elephant.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/huge
  - cr/8
  - source/crcotn
---
###### Ruidium Elephant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Ruidium Elephant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Huge Construct |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 138 (12d12 + 60) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 9 | 21 | 3 | 11 | 6 |
| **Mod** | +7 | -1 | +5 | -4 | +0 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** —
**Condition Immunities:** charmed; frightened

---

### Traits

**Trampling Charge.** If the elephant moves at least 20 feet straight toward a creature and then hits it with a Gore attack on the same turn, that target must succeed on a DC 16 Strength saving throw or be knocked prone. If the target is prone, the elephant can make one Stomp attack against it as a bonus action.


---

### Actions

**Gore.** Melee Weapon Attack: +10 to hit (with advantage if the target is a creature missing any hit points), reach 10 ft., one target. *Hit:* 25 (4d8 + 7) piercing damage plus 7 (2d6) psychic damage.

**Stomp.** Melee Weapon Attack: +10 to hit, reach 5 ft., one prone creature. *Hit:* 29 (4d10 + 7) bludgeoning damage plus 7 (2d6) psychic damage.


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
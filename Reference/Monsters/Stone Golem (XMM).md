---
type: pc
race: "Construct"
class:
 - "Stone Golem"
subClass:
 - "CR 10"
cover: "Stone Golem.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/10
  - source/xmm
---
###### Stone Golem
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Stone Golem.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 220 (21d10 + 105) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 9 | 20 | 3 | 11 | 1 |
| **Mod** | +6 | -1 | +5 | -4 | +0 | -5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 10
**Languages:** understands Common plus two other languages but can't speak
**Damage Immunities:** poison; psychic
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Immutable Form.** The golem can't shape-shift.

**Magic Resistance.** The golem has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The golem makes two attacks, using Slam or Force Bolt in any combination.

**Slam.** m +10, reach 5 ft. *Hit:* 15 (2d8 + 6) Bludgeoning damage plus 9 (2d8) Force damage.

**Force Bolt.** r +9, range 120 ft. *Hit:* 22 (4d10) Force damage.


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
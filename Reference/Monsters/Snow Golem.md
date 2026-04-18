---
type: pc
race: "Construct"
class:
 - "Snow Golem"
subClass:
 - "CR 3"
cover: "Snow Golem.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/3
  - source/idrotf
---
###### Snow Golem
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Snow Golem.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 8 |
> | :FasHeart: HP | 39 (6d8 + 12) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 6 | 14 | 1 | 6 | 1 |
| **Mod** | +2 | -2 | +2 | -5 | -2 | -5 |

**Speed:** 10 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 8
**Languages:** —
**Damage Vulnerabilities:** fire
**Damage Immunities:** cold; poison; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Cold Absorption.** Whenever the golem is subjected to cold damage, it takes no damage and instead regains a number of hit points equal to the cold damage dealt.

**Immutable Form.** The golem is immune to any spell or effect that would alter its form.

**Melt.** While in an area of extreme heat, the golem loses 1d6 hit points at the start of each of its turns.

**Unusual Nature.** The golem doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The golem makes three melee attacks.

**Slam.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) bludgeoning damage plus 7 (2d6) cold damage.

**Snowball.** Ranged Weapon Attack: +0 to hit, range 60 ft., one target. *Hit:* 9 (2d6 + 2) cold damage.


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
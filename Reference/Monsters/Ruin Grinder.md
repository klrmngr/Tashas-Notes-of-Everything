---
type: pc
race: "Construct"
class:
 - "Ruin Grinder"
subClass:
 - "CR 5"
cover: "Ruin Grinder.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/5
  - source/scc
---
###### Ruin Grinder
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Ruin Grinder.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 82 (11d10 + 22) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 13 | 15 | 3 | 10 | 1 |
| **Mod** | +6 | +1 | +2 | -4 | +0 | -5 |

**Speed:** 30 ft., burrow 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 10
**Languages:** understands the languages of its creator but can't speak
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; exhaustion; frightened; petrified; poisoned

---

### Traits

**Fire Absorption.** Whenever the ruin grinder is subjected to fire damage, it regains a number of hit points equal to half the fire damage dealt.

**Siege Monster.** The ruin grinder deals double damage to objects and structures.

**Tunneler.** The ruin grinder can burrow through solid rock at half its burrowing speed and leaves a 10-foot-diameter tunnel in its wake.


---

### Actions

**Multiattack.** The ruin grinder makes two Excavator attacks.

**Excavator.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 13 (2d6 + 6) force damage. If the target is a Huge or smaller creature, it must succeed on a DC 17 Strength saving throw or be pushed up to 10 feet away and knocked prone.


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
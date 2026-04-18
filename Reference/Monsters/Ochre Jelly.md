---
type: pc
race: "Ooze"
class:
 - "Ochre Jelly"
subClass:
 - "CR 2"
cover: "Ochre Jelly.png"
campaign:
locations:
tags:
  - race/ooze
  - affinity/hostile
  - type/ooze
  - size/large
  - cr/2
  - source/mm
---
###### Ochre Jelly
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Ochre Jelly.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Ooze |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 8 |
> | :FasHeart: HP | 45 (6d10 + 12) |
> | :FasUserGroup: Race | Ooze |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 6 | 14 | 2 | 6 | 1 |
| **Mod** | +2 | -2 | +2 | -4 | -2 | -5 |

**Speed:** 10 ft., climb 10 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 8
**Languages:** —
**Damage Resistances:** acid
**Damage Immunities:** lightning; slashing
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; prone

---

### Traits

**Amorphous.** The jelly can move through a space as narrow as 1 inch wide without squeezing.

**Spider Climb.** The jelly can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Pseudopod.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 9 (2d6 + 2) bludgeoning damage plus 3 (1d6) acid damage.


---

### Reactions

**Split.** When a jelly that is Medium or larger is subjected to lightning or slashing damage, it splits into two new jellies if it has at least 10 hit points. Each new jelly has hit points equal to half the original jelly's, rounded down. New jellies are one size smaller than the original jelly.


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
---
type: pc
race: "Humanoid (dire corby)"
class:
 - "Dire Corby"
subClass:
 - "CR 1/2"
cover: "Dire Corby.png"
campaign:
locations:
tags:
  - race/dire corby
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-2
  - source/mff
---
###### Dire Corby
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MFF
___

> [!infobox|no-t right]
> ![[Dire Corby.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dire corby) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 16 (3d8 + 3) |
> | :FasUserGroup: Race | Humanoid (dire corby) |
> | :FasBook: Source | MFF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 14 | 13 | 6 | 8 | 7 |
| **Mod** | +1 | +2 | +1 | -2 | -1 | -2 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Undercommon
**Skills:** Acrobatics +4, Perception +3
**Damage Vulnerabilities:** thunder
**Condition Immunities:** frightened

---

### Traits

**Dire Cacophony.** Any creature other than a dire corby that starts its turn within 60 feet of a dire corby and can hear it must make a DC 11 Wisdom saving throw. On a failed save, the creature is unable to use the Dash action, cannot climb, or cast spells other than cantrips until the start of its next turn.

**Keen Hearing.** The dire corby has advantage on Wisdom (Perception) checks that rely on hearing.


---

### Actions

**Multiattack.** The dire corby makes two claw attacks.

**Claw.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) slashing damage.


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
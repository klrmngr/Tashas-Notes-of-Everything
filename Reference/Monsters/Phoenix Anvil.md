---
type: pc
race: "Humanoid (human)"
class:
 - "Phoenix Anvil"
subClass:
 - "CR 2"
cover: "Phoenix Anvil.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/ai
---
###### Phoenix Anvil
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Acquisitions Incorporated
___

> [!infobox|no-t right]
> ![[Phoenix Anvil.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 18 (chain mail, shield) |
> | :FasHeart: HP | 27 (5d8 + 5) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Acquisitions Incorporated |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 10 | 12 | 13 | 16 | 13 |
| **Mod** | +2 | +0 | +1 | +1 | +3 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Elvish
**Skills:** Athletics +4, Performance +3, Persuasion +3, Religion +3

---

### Traits

**Divine Display (1/Day).** As a bonus action, Phoenix causes his shield to flare with divine light. Each creature of his choice within 30 feet of him must succeed on a DC 13 Wisdom saving throw or be blinded for 1 minute. A creature can repeat the save at the end of each of its turns, ending the effect on itself with a success.


---

### Actions

**Multiattack.** Phoenix makes two melee attacks.

**Warhammer.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) bludgeoning damage, and the target must succeed on a DC 12 Strength saving throw or be pushed 5 feet.


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
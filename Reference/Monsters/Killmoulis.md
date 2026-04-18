---
type: pc
race: "Fey"
class:
 - "Killmoulis"
subClass:
 - "CR 0"
cover: "Killmoulis.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/tiny
  - cr/0
  - source/mff
---
###### Killmoulis
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MFF
___

> [!infobox|no-t right]
> ![[Killmoulis.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Tiny Fey |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 7 (2d4 + 2) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | MFF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 4 | 19 | 13 | 12 | 14 | 13 |
| **Mod** | -3 | +4 | +1 | +1 | +2 | +1 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 30 ft., passive Perception 14
**Languages:** Common, Sylvan, telepathy 60 ft.
**Skills:** History +3, Perception +4, Stealth +8

---

### Actions

**Slam.** Melee Weapon Attack: -1 to hit, reach 5 ft., one target. *Hit:* 1 bludgeoning damage.

**Blessing of Bountiful Generosity (1/Day).** The killmoulis targets up to eight creatures within 100 feet of it that it can see. The next time a target finishes a long rest, it regains all spent Hit Dice and gains 10 temporary hit points.

**Curse of Poor Hospitality (1/Day).** The killmoulis targets up to eight creatures within 100 feet of it that it can see. The next time a target completes a long rest, it does not regain spent Hit Dice.


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
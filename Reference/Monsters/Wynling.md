---
type: pc
race: "Fey"
class:
 - "Wynling"
subClass:
 - "CR 1/2"
cover: "Wynling.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/tiny
  - cr/1-2
  - source/jttrc
---
###### Wynling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: JttRC
___

> [!infobox|no-t right]
> ![[Wynling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Tiny Fey |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 21 (6d4 + 6) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | JttRC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 3 | 20 | 13 | 10 | 14 | 16 |
| **Mod** | -4 | +5 | +1 | +0 | +2 | +3 |

**Speed:** 30 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Sylvan
**Skills:** Sleight Of Hand +7, Stealth +7

---

### Actions

**Slam.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d4 + 5) bludgeoning damage.

**Cloak of the Mountain (Recharge 4–6).** The wynling magically turns invisible, along with any equipment it is wearing or carrying, for 1 minute or until it makes an attack roll.


---

### Reactions

**Trickster's Flight.** Immediately after a creature the wynling can see misses the wynling with an attack roll, the wynling can move up to 30 feet. This movement doesn't provoke opportunity attacks.


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
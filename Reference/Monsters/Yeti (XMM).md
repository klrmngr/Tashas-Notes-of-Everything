---
type: pc
race: "Monstrosity"
class:
 - "Yeti"
subClass:
 - "CR 3"
cover: "Yeti.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/3
  - source/xmm
---
###### Yeti
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Yeti.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 51 (6d10 + 18) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 13 | 16 | 8 | 12 | 7 |
| **Mod** | +4 | +1 | +3 | -1 | +1 | -2 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 15
**Languages:** Yeti
**Skills:** Perception +5, Stealth +5
**Damage Immunities:** cold

---

### Traits

**Fear of Fire.** If the yeti takes Fire damage, it has Disadvantage on attack rolls and ability checks until the end of its next turn.


---

### Actions

**Multiattack.** The yeti can use its Chilling Gaze and makes two attacks, using Claw or Ice Throw in any combination.

**Claw.** m +6, reach 5 ft. *Hit:* 7 (1d6 + 4) Slashing damage plus 3 (1d6) Cold damage.

**Ice Throw.** r +6, range 30/120 ft. *Hit:* 6 (1d4 + 4) Bludgeoning damage plus 2 (1d4) Cold damage.

**Chilling Gaze.** con DC 13, one creature the yeti can see within 30 feet.  5 (2d4) Cold damage, and the target has the Paralyzed condition until the start of the yeti's next turn unless the target has Immunity to Cold damage.  The target is immune to the Chilling Gaze of all yetis (but not abominable yetis) for 1 hour.


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
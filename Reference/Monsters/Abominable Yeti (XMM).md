---
type: pc
race: "Monstrosity"
class:
 - "Abominable Yeti"
subClass:
 - "CR 9"
cover: "Abominable Yeti.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/huge
  - cr/9
  - source/xmm
---
###### Abominable Yeti
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Abominable Yeti.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Huge Monstrosity |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 137 (11d12 + 66) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 10 | 22 | 9 | 13 | 9 |
| **Mod** | +7 | +0 | +6 | -1 | +1 | -1 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 19
**Languages:** Yeti
**Skills:** Perception +9, Stealth +8
**Damage Immunities:** cold

---

### Traits

**Fear of Fire.** If the yeti takes Fire damage, it has Disadvantage on attack rolls and ability checks until the end of its next turn.


---

### Actions

**Multiattack.** The yeti can use its Chilling Gaze and makes two attacks, using Claw or Ice Throw in any combination.

**Claw.** m +11, reach 5 ft. *Hit:* 14 (2d6 + 7) Slashing damage plus 7 (2d6) Cold damage.

**Ice Throw.** r +11, range 60/240 ft. *Hit:* 12 (2d4 + 7) Bludgeoning damage plus 7 (2d6) Cold damage.

**Chilling Gaze.** con DC 18, one creature the yeti can see within 30 feet.  21 (6d6) Cold damage, and the target has the Paralyzed condition until the start of the yeti's next turn unless the target has Immunity to Cold damage.  The target is immune to this yeti's Chilling Gaze for 1 hour.

**Cold Breath (Recharge 6).** con DC 18, each creature in a 30-foot Cone.  45 (10d8) Cold damage.  Half damage.


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
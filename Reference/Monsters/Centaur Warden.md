---
type: pc
race: "Fey"
class:
 - "Centaur Warden"
subClass:
 - "CR 7"
cover: "Centaur Warden.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/large
  - cr/7
  - source/xmm
---
###### Centaur Warden
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Centaur Warden.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Fey |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 105 (14d10 + 28) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 14 | 9 | 18 | 11 |
| **Mod** | +4 | +2 | +2 | -1 | +4 | +0 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 17
**Languages:** Druidic, Elvish, Sylvan
**Saving Throws:** Con +5, Wis +7
**Skills:** Athletics +7, Nature +5, Perception +7

---

### Actions

**Multiattack.** The centaur makes two attacks, using Forest Staff or Sun Ray in any combination.

**Forest Staff.** m +7, reach 5 ft. *Hit:* 13 (2d8 + 4) Bludgeoning damage plus 14 (4d6) Poison damage.

**Sun Ray.** r +7, range 90 ft. *Hit:* 14 (3d6 + 4) Radiant damage, and the target has the Blinded condition until the start of the centaur's next turn.


---

### Bonus Actions

**Entangling Trail (Recharge 5–6).** The centaur moves up to its Speed without provoking Opportunity Attacks. Each creature within 5 feet of the centaur as it moves is targeted once by the following effect. str DC 15.  11 (2d6 + 4) Bludgeoning damage, and the target has the Restrained condition until the end of its next turn.


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
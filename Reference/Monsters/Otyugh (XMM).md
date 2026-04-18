---
type: pc
race: "Aberration"
class:
 - "Otyugh"
subClass:
 - "CR 5"
cover: "Otyugh.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/5
  - source/xmm
---
###### Otyugh
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Otyugh.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 104 (11d10 + 44) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 11 | 19 | 6 | 13 | 6 |
| **Mod** | +3 | +0 | +4 | -2 | +1 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 11
**Languages:** Otyugh; telepathy 120 ft. (doesn't allow the receiving creature to respond telepathically)
**Saving Throws:** Con +7

---

### Actions

**Multiattack.** The otyugh makes one Bite attack and two Tentacle attacks.

**Bite.** m +6, reach 5 ft. *Hit:* 12 (2d8 + 3) Piercing damage, and the target has the Poisoned condition. Whenever the Poisoned target finishes a Long Rest, it is subjected to the following effect. con DC 15.  The target's Hit Point maximum decreases by 5 (1d10) and doesn't return to normal until the Poisoned condition ends on the target.  The Poisoned condition ends.

**Tentacle.** m +6, reach 10 ft. *Hit:* 12 (2d8 + 3) Piercing damage. If the target is a Medium or smaller creature, it has the Grappled condition (escape DC 13) from one of two tentacles.

**Tentacle Slam.** con DC 14, each creature Grappled by the otyugh.  16 (3d8 + 3) Bludgeoning damage, and the target has the Stunned condition until the start of the otyugh's next turn.  Half damage only.


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
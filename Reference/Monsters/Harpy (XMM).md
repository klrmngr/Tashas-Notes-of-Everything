---
type: pc
race: "Monstrosity"
class:
 - "Harpy"
subClass:
 - "CR 1"
cover: "Harpy.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/1
  - source/xmm
---
###### Harpy
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Harpy.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 38 (7d8 + 7) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 13 | 12 | 7 | 10 | 13 |
| **Mod** | +1 | +1 | +1 | -2 | +0 | +1 |

**Speed:** 20 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common

---

### Actions

**Claw.** m +3, reach 5 ft. *Hit:* 6 (2d4 + 1) Slashing damage.

**Luring Song.** The harpy sings a magical melody, which lasts until the harpy's Concentration ends on it. wis DC 11, each Humanoid and Giant in a 300-foot Emanation originating from the harpy when the song starts.  The target has the Charmed condition until the song ends and repeats the save at the end of each of its turns. While Charmed, the target has the Incapacitated condition and ignores the Luring Song of other harpies. If the target is more than 5 feet from the harpy, the target moves on its turn toward the harpy by the most direct route, trying to get within 5 feet of the harpy. It doesn't avoid Opportunity Attacks; however, before moving into damaging terrain (such as lava or a pit) and whenever it takes damage from a source other than the harpy, the target repeats the save.  The target is immune to this harpy's Luring Song for 24 hours.


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
---
type: pc
race: "Beast (dinosaur)"
class:
 - "Allosaurus"
subClass:
 - "CR 2"
cover: "Allosaurus.png"
campaign:
locations:
tags:
  - race/dinosaur
  - affinity/hostile
  - type/beast
  - size/large
  - cr/2
  - source/xmm
---
###### Allosaurus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Allosaurus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Beast (dinosaur) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 51 (6d10 + 18) |
> | :FasUserGroup: Race | Beast (dinosaur) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 13 | 17 | 2 | 12 | 5 |
| **Mod** | +4 | +1 | +3 | -4 | +1 | -3 |

**Speed:** 60 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** —
**Skills:** Perception +5

---

### Actions

**Bite.** m +6, reach 5 ft. *Hit:* 15 (2d10 + 4) Piercing damage.

**Claws.** m +6, reach 5 ft. *Hit:* 8 (1d8 + 4) Slashing damage. If the target is a Large or smaller creature and the allosaurus moved 30+ feet straight toward it immediately before the hit, the target has the Prone condition, and the allosaurus can make one Bite attack against it.


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
---
type: pc
race: "Beast"
class:
 - "Relic Sloth"
subClass:
 - "CR 2"
cover: "Relic Sloth.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/huge
  - cr/2
  - source/scc
---
###### Relic Sloth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Relic Sloth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Huge Beast |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 76 (8d12 + 24) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 9 | 17 | 2 | 12 | 8 |
| **Mod** | +5 | -1 | +3 | -4 | +1 | -1 |

**Speed:** 20 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** —
**Skills:** Perception +3

---

### Actions

**Claws.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 14 (2d8 + 5) slashing damage, and the target is grappled (escape DC 15). The relic sloth can grapple no more than two targets at a time.


---

### Reactions

**Slow but Sturdy.** When the relic sloth is subjected to an effect that would move it out of its current space or knock it prone, it is neither moved nor knocked prone.


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
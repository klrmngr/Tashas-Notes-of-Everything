---
type: pc
race: "Monstrosity"
class:
 - "Phase Spider"
subClass:
 - "CR 3"
cover: "Phase Spider.png"
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
###### Phase Spider
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Phase Spider.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 45 (7d10 + 7) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 16 | 12 | 6 | 10 | 6 |
| **Mod** | +2 | +3 | +1 | -2 | +0 | -2 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** —
**Skills:** Stealth +7

---

### Traits

**Ethereal Sight.** The spider can see 60 feet into the Ethereal Plane while on the Material Plane and vice versa.

**Spider Climb.** The spider can climb difficult surfaces, including along ceilings, without needing to make an ability check.

**Web Walker.** The spider ignores movement restrictions caused by webs, and the spider knows the location of any other creature in contact with the same web.


---

### Actions

**Multiattack.** The spider makes two Bite attacks.

**Bite.** m +5, reach 5 ft. *Hit:* 8 (1d10 + 3) Piercing damage plus 9 (2d8) Poison damage. If this damage reduces the target to 0 Hit Points, the target becomes Stable, and it has the Poisoned condition for 1 hour. While Poisoned, the target also has the Paralyzed condition.


---

### Bonus Actions

**Ethereal Jaunt.** The spider teleports from the Material Plane to the Ethereal Plane or vice versa.


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
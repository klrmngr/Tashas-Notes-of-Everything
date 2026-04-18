---
type: pc
race: "Plant"
class:
 - "Myconid Sprout"
subClass:
 - "CR 0"
cover: "Myconid Sprout.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/small
  - cr/0
  - source/xmm
---
###### Myconid Sprout
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Myconid Sprout.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Small Plant |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 3 (1d6) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 10 | 10 | 8 | 11 | 5 |
| **Mod** | -1 | +0 | +0 | -1 | +0 | -3 |

**Speed:** 10 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 10
**Languages:** telepathy 240 ft.

---

### Traits

**Sun Sickness.** While in sunlight, the myconid has Disadvantage on D20 Tests. The myconid dies if it spends more than 1 hour in sunlight.


---

### Actions

**Slam.** m +1, reach 5 ft. *Hit:* 1 (1d4 - 1) Bludgeoning damage plus 2 (1d4) Poison damage.

**Rapport Spores.** The myconid expels spores in a 30-foot Emanation originating from itself. Creatures in that area with an Intelligence score of 2 or higher that aren't Constructs, Elementals, or Undead gain telepathy with a range of 30 feet for 1 hour.


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
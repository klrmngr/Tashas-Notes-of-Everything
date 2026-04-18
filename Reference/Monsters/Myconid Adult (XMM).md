---
type: pc
race: "Plant"
class:
 - "Myconid Adult"
subClass:
 - "CR 1/2"
cover: "Myconid Adult.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/medium
  - cr/1-2
  - source/xmm
---
###### Myconid Adult
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Myconid Adult.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Plant |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 16 (3d8 + 3) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 10 | 12 | 10 | 13 | 7 |
| **Mod** | +0 | +0 | +1 | +0 | +1 | -2 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 11
**Languages:** telepathy 240 ft.

---

### Traits

**Sun Sickness.** While in sunlight, the myconid has Disadvantage on D20 Tests. The myconid dies if it spends more than 1 hour in sunlight.


---

### Actions

**Slam.** m +2, reach 5 ft. *Hit:* 4 (1d8) Bludgeoning damage plus 3 (1d6) Poison damage.

**Pacifying Spores (1/Day).** con DC 11, one creature the myconid can see within 10 feet.  The target has the Stunned condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.

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
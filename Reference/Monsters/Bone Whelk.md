---
type: pc
race: "Monstrosity"
class:
 - "Bone Whelk"
subClass:
 - "CR 1/4"
cover: "Bone Whelk.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/1-4
  - source/bgdia
---
###### Bone Whelk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGDIA
___

> [!infobox|no-t right]
> ![[Bone Whelk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 (natural armor) |
> | :FasHeart: HP | 27 (5d10) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | BGDIA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 5 | 11 | 6 | 9 | 3 |
| **Mod** | +0 | -3 | +0 | -2 | -1 | -4 |

**Speed:** 15 ft., climb 15 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 9
**Languages:** —

---

### Traits

**Adhesive.** The bone whelk can cause Medium or smaller objects to adhere to it. A Medium or smaller creature that touches the bone whelk is grappled by it (escape DC 10).

**Death Scream.** When the bone whelk dies, it emits a blood-curdling shriek than can be heard out to a range of 120 feet. This shriek causes nonmagical, organic material within 10 feet of the bone whelk to rot. Each creature within 10 feet of the bone whelk when it dies takes 9 (2d8) necrotic damage.

**Spider Climb.** The bone whelk can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Bite.** Melee Weapon Attack: +2 to hit, reach 5 ft., one creature. *Hit:* 4 (1d8) piercing damage.


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
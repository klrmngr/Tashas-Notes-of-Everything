---
type: pc
race: "Plant"
class:
 - "Campestri"
subClass:
 - "CR 0"
cover: "Campestri.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/tiny
  - cr/0
  - source/wbtw
---
###### Campestri
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Campestri.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Tiny Plant |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 (natural armor) |
> | :FasHeart: HP | 2 (1d4) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 7 | 10 | 4 | 10 | 8 |
| **Mod** | -5 | -2 | +0 | -3 | +0 | -1 |

**Speed:** 5 ft. &nbsp;|&nbsp; **Senses:** tremorsense 30 ft., passive Perception 14
**Languages:** understands Common but speaks only through the use of its Mimicry trait
**Skills:** Perception +4

---

### Traits

**Mimicry.** The campestri can mimic any voice or song it has heard, albeit in a nasal falsetto.


---

### Actions

**Head Butt.** Melee Weapon Attack: +0 to hit, reach 5 ft., one target. *Hit:* 1 bludgeoning damage.

**Spores (1/Day).** A 5-foot radius of spores extends from the campestri. These spores can go around corners, and they have no effect on Constructs, Elementals, Plants, or Undead. Each other creature in the area must make a DC 10 Wisdom saving throw. On a failed save, the creature is incapacitated and its speed is halved, both for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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
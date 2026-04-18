---
type: pc
race: "Aberration"
class:
 - "Cranium Rat Squeaker"
subClass:
 - "CR 0"
cover: "Cranium Rat Squeaker.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/tiny
  - cr/0
  - source/mpp
---
###### Cranium Rat Squeaker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Cranium Rat Squeaker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Tiny Aberration |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 2 (1d4) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 2 | 14 | 10 | 4 | 11 | 8 |
| **Mod** | -4 | +2 | +0 | -3 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 30 ft., passive Perception 10
**Languages:** telepathy 30 ft. (emotions only)

---

### Traits

**Shared Telepathy.** Any creature touching the cranium rat can use the rat's telepathy if the rat allows it. If the creature knows any language, the creature can use the telepathy to communicate words and emotions.

**Telepathic Shroud.** The cranium rat is immune to any effect that would sense its emotions or read its thoughts, as well as to divination spells.


---

### Actions

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 1 piercing damage.


---

### Bonus Actions

**Illumination.** The cranium rat sheds dim light from its exposed brain in a 5-foot radius or extinguishes the light.


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
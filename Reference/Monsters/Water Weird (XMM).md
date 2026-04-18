---
type: pc
race: "Elemental"
class:
 - "Water Weird"
subClass:
 - "CR 3"
cover: "Water Weird.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/3
  - source/xmm
---
###### Water Weird
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Water Weird.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Elemental |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 65 (10d10 + 10) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 16 | 13 | 11 | 10 | 10 |
| **Mod** | +3 | +3 | +1 | +0 | +0 | +0 |

**Speed:** 5 ft., swim 60 ft. &nbsp;|&nbsp; **Senses:** Blindsight 30 ft., passive Perception 10
**Languages:** understands Primordial but can't speak
**Damage Resistances:** fire
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; grappled; paralyzed; petrified; poisoned; prone; restrained; unconscious

---

### Traits

**Invisible in Water.** The water weird has the Invisible condition while fully immersed in water.

**Water Bound.** The water weird dies if it leaves the water to which it is bound or if that water is destroyed.


---

### Actions

**Surge.** m +5, reach 10 ft. *Hit:* 13 (3d6 + 3) Cold damage. If the target is a Medium or smaller creature, it has the Grappled condition (escape DC 13), and it has the Restrained condition until the grapple ends.


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
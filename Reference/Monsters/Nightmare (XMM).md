---
type: pc
race: "Fiend"
class:
 - "Nightmare"
subClass:
 - "CR 3"
cover: "Nightmare.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/3
  - source/xmm
---
###### Nightmare
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Nightmare.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Fiend |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 68 (8d10 + 24) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 16 | 10 | 13 | 15 |
| **Mod** | +4 | +2 | +3 | +0 | +1 | +2 |

**Speed:** 60 ft., fly 90 ft. ((hover)) &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** understands Abyssal, Common, and Infernal but can't speak
**Damage Immunities:** fire

---

### Traits

**Confer Fire Resistance.** The nightmare can grant Resistance to Fire damage to a rider while it is on the nightmare.

**Illumination.** The nightmare sheds Bright Light in a 10-foot radius and Dim Light for an additional 10 feet.


---

### Actions

**Hooves.** m +6, reach 5 ft. *Hit:* 13 (2d8 + 4) Bludgeoning damage plus 10 (3d6) Fire damage.

**Ethereal Stride.** The nightmare and up to three willing creatures within 5 feet of it teleport to the Ethereal Plane from the Material Plane or vice versa.


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
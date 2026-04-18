---
type: pc
race: "Humanoid"
class:
 - "Elemental Cultist"
subClass:
 - "CR 8"
cover: "Elemental Cultist.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/8
  - source/xmm
---
###### Elemental Cultist
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Elemental Cultist.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 135 (18d8 + 54) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 12 | 16 | 14 | 18 | 12 |
| **Mod** | +4 | +1 | +3 | +2 | +4 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 17
**Languages:** Common, Primordial
**Saving Throws:** Con +6, Wis +7
**Skills:** Arcana +5, Perception +7, Religion +5

---

### Actions

**Multiattack.** The cultist makes three attacks, using Elemental Flail or Elemental Claw in any combination.

**Elemental Flail.** m +7, reach 5 ft. *Hit:* 25 (6d6 + 4) damage of a type chosen by the cultist: Acid, Cold, Fire, Lightning, or Thunder.

**Elemental Claw.** r +7, range 120 ft. *Hit:* 22 (4d10) damage of a type chosen by the cultist: Acid, Cold, Fire, Lightning, or Thunder. If the target is a Medium or smaller creature, the cultist moves the target up to 10 feet straight toward or away from itself.


---

### Reactions

**Elemental Absorption (1/Day).**  The cultist takes Acid, Cold, Fire, Lightning, or Thunder damage.  The cultist gives itself Resistance to that instance of damage and gains 10 Temporary Hit Points.


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
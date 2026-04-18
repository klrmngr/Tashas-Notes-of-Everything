---
type: pc
race: "Elemental"
class:
 - "Earth Elemental"
subClass:
 - "CR 5"
cover: "Earth Elemental.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/5
  - source/xmm
---
###### Earth Elemental
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Earth Elemental.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Elemental |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 147 (14d10 + 70) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 8 | 20 | 5 | 10 | 5 |
| **Mod** | +5 | -1 | +5 | -3 | +0 | -3 |

**Speed:** 30 ft., burrow 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., Tremorsense 60 ft., passive Perception 10
**Languages:** Primordial (Terran)
**Damage Vulnerabilities:** thunder
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; paralyzed; petrified; poisoned; unconscious

---

### Traits

**Earth Glide.** The elemental can burrow through nonmagical, unworked earth and stone. While doing so, the elemental doesn't disturb the material it moves through.

**Siege Monster.** The elemental deals double damage to objects and structures.


---

### Actions

**Multiattack.** The elemental makes two attacks, using Slam or Rock Launch in any combination.

**Slam.** m +8, reach 10 ft. *Hit:* 14 (2d8 + 5) Bludgeoning damage.

**Rock Launch.** r +8, range 60 ft. *Hit:* 8 (1d6 + 5) Bludgeoning damage. If the target is a Large or smaller creature, it has the Prone condition.


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
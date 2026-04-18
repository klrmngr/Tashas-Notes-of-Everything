---
type: pc
race: "Monstrosity"
class:
 - "Chimera"
subClass:
 - "CR 6"
cover: "Chimera.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/6
  - source/xmm
---
###### Chimera
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Chimera.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 114 (12d10 + 48) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 11 | 19 | 3 | 14 | 10 |
| **Mod** | +4 | +0 | +4 | -4 | +2 | +0 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 18
**Languages:** understands Draconic but can't speak
**Skills:** Perception +8

---

### Actions

**Multiattack.** The chimera makes one Ram attack, one Bite attack, and one Claw attack. It can replace the Claw attack with a use of Fire Breath if available.

**Bite.** m +7, reach 5 ft. *Hit:* 11 (2d6 + 4) Piercing damage, or 18 (4d6 + 4) Piercing damage if the chimera had Advantage on the attack roll.

**Claw.** m +7, reach 5 ft. *Hit:* 7 (1d6 + 4) Slashing damage.

**Ram.** m +7, reach 5 ft. *Hit:* 10 (1d12 + 4) Bludgeoning damage. If the target is a Medium or smaller creature, it has the Prone condition.

**Fire Breath (Recharge 5–6).** dex DC 15, each creature in a 15-foot Cone.  31 (7d8) Fire damage.  Half damage.


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
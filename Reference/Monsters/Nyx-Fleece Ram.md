---
type: pc
race: "Monstrosity"
class:
 - "Nyx-Fleece Ram"
subClass:
 - "CR 1"
cover: "Nyx-Fleece Ram.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/1
  - source/mot
---
###### Nyx-Fleece Ram
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Nyx-Fleece Ram.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 27 (5d8 + 5) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 12 | 3 | 13 | 10 |
| **Mod** | +3 | +2 | +1 | -4 | +1 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** —

---

### Traits

**Charge.** If the ram moves at least 20 feet straight toward a target and then hits it with a ram attack on the same turn, the target takes an extra 5 (2d4) bludgeoning damage. If the target is a creature, it must succeed on a DC 13 Strength saving throw or be knocked prone.

**Magic Resistance.** The ram has advantage on saving throws against spells and other magical effects.

**Sure-Footed.** The ram has advantage on Strength and Dexterity saving throws against effects that would knock it prone.


---

### Actions

**Ram.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 8 (2d4 + 3) bludgeoning damage plus 3 (1d6) force damage.


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
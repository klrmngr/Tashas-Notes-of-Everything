---
type: pc
race: "Humanoid (triton)"
class:
 - "Triton Shorestalker"
subClass:
 - "CR 2"
cover: "Triton Shorestalker.png"
campaign:
locations:
tags:
  - race/triton
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/mot
---
###### Triton Shorestalker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Triton Shorestalker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (triton) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 32 (5d8 + 10) |
> | :FasUserGroup: Race | Humanoid (triton) |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 16 | 14 | 10 | 15 | 11 |
| **Mod** | +0 | +3 | +2 | +0 | +2 | +0 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Common, Primordial
**Skills:** Nature +4, Perception +4, Stealth +5
**Damage Resistances:** cold

---

### Traits

**Amphibious.** The triton can breathe air and water.

**Nimble Escape.** The triton can take the Disengage or Hide actions as a bonus action on each of its turns.


---

### Actions

**Multiattack.** The triton makes two urchin-spine shortsword attacks.

**Urchin-Spine Shortsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage plus 10 (3d6) poison damage. If the damage reduces a creature to 0 hit points, that creature is stable but poisoned for 1 hour, even after regaining hit points, and is paralyzed while poisoned in this way.

**Poisoned Spine.** Ranged Weapon Attack: +5 to hit, range 30/60 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage plus 10 (3d6) poison damage.


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
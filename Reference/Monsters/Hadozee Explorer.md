---
type: pc
race: "Humanoid"
class:
 - "Hadozee Explorer"
subClass:
 - "CR 2"
cover: "Hadozee Explorer.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/bam
---
###### Hadozee Explorer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Hadozee Explorer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 15 (studded leather) |
> | :FasHeart: HP | 49 (9d8 + 9) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 17 | 13 | 13 | 17 | 14 |
| **Mod** | +0 | +3 | +1 | +1 | +3 | +2 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common, Hadozee
**Saving Throws:** Con +3, Wis +5
**Skills:** Athletics +2, Perception +5, Stealth +5, Survival +5

---

### Traits

**Glide.** If it isn't incapacitated or wearing heavy armor, the hadozee can extend its skin membranes to move up to 5 feet horizontally for every 1 foot it descends in the air.


---

### Actions

**Multiattack.** The hadozee makes two Shortsword attacks.

**Shortsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.

**Musket.** Ranged Weapon Attack: +5 to hit, range 40/120 ft., one target. *Hit:* 16 (2d12 + 3) piercing damage.


---

### Bonus Actions

**Nimble Escape.** The hadozee takes the Disengage or Hide action.


---

### Reactions

**Safe Descent.** When it would take damage from a fall, the hadozee extends its skin membranes to reduce the fall's damage to 0, provided it isn't wearing heavy armor.


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
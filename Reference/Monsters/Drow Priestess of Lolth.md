---
type: pc
race: "Humanoid (elf)"
class:
 - "Drow Priestess of Lolth"
subClass:
 - "CR 8"
cover: "Drow Priestess of Lolth.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/8
  - source/fraif
---
###### Drow Priestess of Lolth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Drow Priestess of Lolth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 99 (18d8 + 18) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 12 | 13 | 18 | 17 |
| **Mod** | +0 | +2 | +1 | +1 | +4 | +3 |

**Speed:** 30 ft., fly 15 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 17
**Languages:** Abyssal, Common, Elvish, Undercommon
**Saving Throws:** Con +4, Wis +7, Cha +6
**Skills:** Insight +7, Perception +7, Religion +4, Stealth +5

---

### Traits

**Fey Ancestry.** The drow has Advantage on saving throws it makes to avoid or end the Charmed condition, and magic can't put the drow to sleep.

**Sunlight Sensitivity.** While in sunlight, the drow has Disadvantage on attack rolls.


---

### Actions

**Multiattack.** The drow makes three Scourge attacks.

**Scourge.** m +5, reach 10 ft. *Hit:* 6 (1d6 + 3) Piercing damage plus 17 (5d6) Poison damage.

**Spider Vortex (Recharge 5–6).** con DC 15, each enemy in a 20-foot Emanation originating from the drow.  33 (6d10) Piercing damage, and the target has the Restrained condition until the start of the drow's next turn.  Half damage only.


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
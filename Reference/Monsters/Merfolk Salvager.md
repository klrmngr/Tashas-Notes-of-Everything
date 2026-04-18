---
type: pc
race: "Humanoid (merfolk)"
class:
 - "Merfolk Salvager"
subClass:
 - "CR 1"
cover: "Merfolk Salvager.png"
campaign:
locations:
tags:
  - race/merfolk
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/gos
---
###### Merfolk Salvager
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Merfolk Salvager.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (merfolk) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 22 (4d8 + 4) |
> | :FasUserGroup: Race | Humanoid (merfolk) |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 14 | 12 | 11 | 10 | 13 |
| **Mod** | +1 | +2 | +1 | +0 | +0 | +1 |

**Speed:** 10 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Aquan, Common
**Saving Throws:** Dex +4
**Skills:** Athletics +3, Perception +2

---

### Traits

**Amphibious.** The salvager can breathe air and water.


---

### Actions

**Multiattack.** The salvager makes two attacks with its coral rapier.

**Coral Rapier.** m attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) piercing damage.

**Inject Toxin (2/Day).** m attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) piercing damage, and the creature must succeed on a DC 12 Constitution saving throw or be paralyzed until the end of its next turn.


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
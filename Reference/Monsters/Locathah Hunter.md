---
type: pc
race: "Humanoid (locathah)"
class:
 - "Locathah Hunter"
subClass:
 - "CR 2"
cover: "Locathah Hunter.png"
campaign:
locations:
tags:
  - race/locathah
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/gos
---
###### Locathah Hunter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Locathah Hunter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (locathah) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Humanoid (locathah) |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 14 | 12 | 11 | 14 | 11 |
| **Mod** | +1 | +2 | +1 | +0 | +2 | +0 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Aquan, Common
**Saving Throws:** Dex +4, Wis +4
**Skills:** Athletics +3, Perception +4

---

### Traits

**Leviathan Will.** The hunter has advantage on saving throws against spells and effects that control its actions.

**Limited Amphibiousness.** The hunter can breathe air and water, but it needs to be submerged at least once every 4 hours to avoid suffocating.


---

### Actions

**Multiattack.** The hunter makes two attacks with its envenomed crossbow.

**Envenomed Crossbow.** Ranged Weapon Attack: +4 to hit, range 80/320 ft., one target. *Hit:* 11 (2d8 + 2) piercing damage, and the target must succeed on a DC 12 Constitution saving throw or be poisoned until the end of its next turn.

**Club.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 4 (1d6 + 1) bludgeoning damage.


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
---
type: pc
race: "Fey"
class:
 - "Satyr Reveler"
subClass:
 - "CR 1"
cover: "Satyr Reveler.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/1
  - source/mot
---
###### Satyr Reveler
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Satyr Reveler.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 16 | 13 | 12 | 10 | 16 |
| **Mod** | +1 | +3 | +1 | +1 | +0 | +3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common, Sylvan
**Skills:** Acrobatics +5, Performance +7, Stealth +5

---

### Traits

**Enthralling Performance.** If the satyr performs for at least 1 minute, it chooses up to four humanoids within 60 feet of it who watched or listened to the entire performance. Each target must succeed on a DC 13 Wisdom saving throw or be charmed. While charmed in this way, the target idolizes the satyr and will take part in the satyr's revels. The charmed condition ends for the creature after 1 hour, if it takes any damage, if the satyr attacks the target, or if the target witnesses the satyr attacking or damaging any of the target's allies.

**Magic Resistance.** The satyr has advantage on saving throws against spells and other magical effects.

**Sleepless Reveler.** Magic can't put the satyr to sleep.


---

### Actions

**Multiattack.** The satyr makes two ram attacks or two shortbow attacks.

**Ram.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 6 (2d4 + 1) bludgeoning damage.

**Shortbow.** Ranged Weapon Attack: +5 to hit, range 80/320 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.


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
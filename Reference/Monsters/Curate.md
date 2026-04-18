---
type: pc
race: "Humanoid"
class:
 - "Curate"
subClass:
 - "CR 6"
cover: "Curate.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/6
  - source/hotb
---
###### Curate
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: HotB
___

> [!infobox|no-t right]
> ![[Curate.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 97 (15d8 + 30) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | HotB |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 14 | 14 | 14 | 18 | 14 |
| **Mod** | -1 | +2 | +2 | +2 | +4 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Celestial, Common
**Saving Throws:** Int +5, Wis +7, Cha +5
**Skills:** Persuasion +5, Religion +5
**Condition Immunities:** charmed; frightened

---

### Traits

**Magic Resistance.** The curate has Advantage on saving throws against spells and other magical effects.

**Raise the Dead (1/Day).** In a ritual that takes 8 hours, the curate touches a creature that has died within the past 7 days. That creature returns to life with 1 Hit Point. The curate can't revive a creature that died of old age.


---

### Actions

**Multiattack.** The curate makes three Celestial Radiance attacks.

**Celestial Radiance.** m,r +7, reach 5 ft. or range 60 ft. *Hit:* 18 (4d8) Radiant damage.

**Healer's Touch (2/Day).** The curate touches another creature. That creature regains 13 (2d8 + 4) Hit Points.


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
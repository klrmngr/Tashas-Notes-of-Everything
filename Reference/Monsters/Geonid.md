---
type: pc
race: "Elemental"
class:
 - "Geonid"
subClass:
 - "CR 1/4"
cover: "Geonid.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/small
  - cr/1-4
  - source/ttp
---
###### Geonid
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: TTP
___

> [!infobox|no-t right]
> ![[Geonid.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Elemental |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 26 (4d6 + 12) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | TTP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 10 | 16 | 9 | 14 | 11 |
| **Mod** | +1 | +0 | +3 | -1 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., tremorsense 30 ft., passive Perception 14
**Languages:** —
**Skills:** Perception +4, Stealth +2

---

### Traits

**Boulder Guise.** While fully withdrawn into its shell, the geonid can't see and is indistinguishable from a small boulder


---

### Actions

**Club.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d4 + 1) bludgeoning damage.

**Stone Tell.** The geonid touches a stone object or surface and knows what types of creatures have been within 10 feet of that stone in the past 24 hours. The geonid can also determine the number of creatures of each type, but not their identities.


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
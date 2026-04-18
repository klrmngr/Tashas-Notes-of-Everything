---
type: pc
race: "Humanoid (merfolk)"
class:
 - "Crystal Cave Merfolk"
subClass:
 - "CR 1/8"
cover: "Crystal Cave Merfolk.png"
campaign:
locations:
tags:
  - race/merfolk
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-8
  - source/awm
---
###### Crystal Cave Merfolk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: AWM
___

> [!infobox|no-t right]
> ![[Crystal Cave Merfolk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Medium Humanoid (merfolk) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 11 |
> | :FasUserGroup: Race | Humanoid (merfolk) |
> | :FasBook: Source | AWM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 13 | 12 | 11 | 11 | 12 |
| **Mod** | +0 | +1 | +1 | +0 | +0 | +1 |

**Speed:** 10 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** —
**Languages:** —

---

### Traits

**Amphibious.** The merfolk can breathe air and water.

**Siren Song.** Lovely singing voices charm every humanoid or giant within 300 feet. The targets must succeed on a DC 11 Wisdom saving throw or be charmed until the song ends.


---

### Actions

**Bite.** Melee Weapon Attack: +2 to hit, one target. *Hit:* 3 (1d6) piercing damage.


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
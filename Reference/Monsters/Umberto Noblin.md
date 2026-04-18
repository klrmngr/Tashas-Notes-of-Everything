---
type: pc
race: "Humanoid (gnome)"
class:
 - "Umberto Noblin"
subClass:
 - "CR —"
cover: "Umberto Noblin.png"
campaign:
locations:
tags:
  - race/gnome
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/—
  - source/veor
---
###### Umberto Noblin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Umberto Noblin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid (gnome) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | — |
> | :FasHeart: HP | — |
> | :FasUserGroup: Race | Humanoid (gnome) |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 10 | 10 | 10 | 10 | 10 |
| **Mod** | +0 | +0 | +0 | +0 | +0 | +0 |

**Speed:** 0 ft. &nbsp;|&nbsp; **Senses:** —
**Languages:** —

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
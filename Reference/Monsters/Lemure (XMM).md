---
type: pc
race: "Fiend (devil)"
class:
 - "Lemure"
subClass:
 - "CR 0"
cover: "Lemure.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/0
  - source/xmm
---
###### Lemure
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Lemure.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Medium Fiend (devil) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 9 |
> | :FasHeart: HP | 9 (2d8) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 5 | 11 | 1 | 11 | 3 |
| **Mod** | +0 | -3 | +0 | -5 | +0 | -4 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft. (unimpeded by magical Darkness), passive Perception 10
**Languages:** understands Infernal but can't speak
**Damage Resistances:** cold
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Hellish Restoration.** If the lemure dies in the Nine Hells, it revives with all its Hit Points in 1d10 days unless it is killed by a creature under the effects of a Bless spell or its remains are sprinkled with Holy Water.


---

### Actions

**Vile Slime.** m +2, reach 5 ft. *Hit:* 2 (1d4) Poison damage.


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
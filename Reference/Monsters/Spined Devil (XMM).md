---
type: pc
race: "Fiend (devil)"
class:
 - "Spined Devil"
subClass:
 - "CR 2"
cover: "Spined Devil.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/small
  - cr/2
  - source/xmm
---
###### Spined Devil
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Spined Devil.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Fiend (devil) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 45 (10d6 + 10) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 15 | 12 | 11 | 14 | 8 |
| **Mod** | +0 | +2 | +1 | +0 | +2 | -1 |

**Speed:** 20 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft. (unimpeded by magical Darkness), passive Perception 12
**Languages:** Infernal; telepathy 120 ft.
**Damage Resistances:** cold
**Damage Immunities:** fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Flyby.** The devil doesn't provoke an Opportunity Attack when it flies out of an enemy's reach.

**Magic Resistance.** The devil has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The devil makes two attacks, using Infernal Fork and Tail Spine in any combination.

**Infernal Fork.** m +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Piercing damage plus 3 (1d6) Fire damage.

**Tail Spine.** r +4, range 20/80 ft. *Hit:* 4 (1d4 + 2) Piercing damage plus 3 (1d6) Fire damage.


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
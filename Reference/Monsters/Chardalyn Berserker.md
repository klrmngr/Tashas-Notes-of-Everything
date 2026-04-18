---
type: pc
race: "Fiend"
class:
 - "Chardalyn Berserker"
subClass:
 - "CR 4"
cover: "Chardalyn Berserker.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/4
  - source/idrotf
---
###### Chardalyn Berserker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Chardalyn Berserker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 (hide armor) |
> | :FasHeart: HP | 90 (12d8 + 36) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 12 | 17 | 9 | 11 | 9 |
| **Mod** | +3 | +1 | +3 | -1 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** any one language (usually Common)
**Skills:** Survival +4

---

### Traits

**Chardalyn Madness.** The berserker must roll a d6 at the start of each of its turns. On a 1, the berserker does nothing on its turn except speak to a nonexistent, evil master whom it has pledged to serve.

**Reckless.** At the start of its turn, the berserker can gain advantage on all melee weapon attack rolls during that turn, but attack rolls against it have advantage until the start of its next turn.


---

### Actions

**Multiattack.** The berserker attacks three times with a melee weapon.

**Chardalyn Flail.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) bludgeoning damage, and the target must succeed on a DC 13 Constitution saving throw or be poisoned until the end of its next turn.

**Chardalyn Javelin.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage, and the target must succeed on a DC 13 Constitution saving throw or be poisoned until the end of its next turn.


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
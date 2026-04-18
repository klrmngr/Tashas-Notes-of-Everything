---
type: pc
race: "Aberration"
class:
 - "Psurlon Ringer"
subClass:
 - "CR 1"
cover: "Psurlon Ringer.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/1
  - source/bam
---
###### Psurlon Ringer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Psurlon Ringer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 13 (mage armor) |
> | :FasHeart: HP | 31 (7d8) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 11 | 10 | 17 | 11 | 7 |
| **Mod** | +0 | +0 | +0 | +3 | +0 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Deep Speech plus the languages of the Humanoid it is imitating, telepathy 120 ft.
**Damage Resistances:** psychic
**Condition Immunities:** charmed

---

### Traits

**Aberrant Mind.** Magic can't read the psurlon's thoughts or put the psurlon to sleep.


---

### Actions

**Dagger.** Melee or Ranged Weapon Attack: +2 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 2 (1d4) piercing damage plus 4 (1d8) psychic damage.

**Psychic Crush.** The psurlon targets one creature it can see within 120 feet of itself. The target must make a DC 13 Wisdom saving throw, taking 12 (3d8 + 3) psychic damage on a failed save, or half as much damage on a successful one.


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
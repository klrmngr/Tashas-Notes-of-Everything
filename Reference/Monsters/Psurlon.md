---
type: pc
race: "Aberration"
class:
 - "Psurlon"
subClass:
 - "CR 2"
cover: "Psurlon.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/2
  - source/bam
---
###### Psurlon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Psurlon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (mage armor) |
> | :FasHeart: HP | 45 (7d8 + 14) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 14 | 14 | 17 | 11 | 7 |
| **Mod** | +2 | +2 | +2 | +3 | +0 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft. (blind beyond this radius), passive Perception 10
**Languages:** Deep Speech, telepathy 120 ft.
**Damage Resistances:** psychic
**Condition Immunities:** blinded; charmed

---

### Traits

**Aberrant Mind.** Magic can't read the psurlon's thoughts or put the psurlon to sleep.


---

### Actions

**Multiattack.** The psurlon makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. *Hit:* 6 (1d8 + 2) piercing damage.

**Claw.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) slashing damage.

**Psychic Crush.** The psurlon targets one creature it can see within 120 feet of itself. The target must make a DC 13 Wisdom saving throw, taking 14 (2d10 + 3) psychic damage on a failed save, or half as much damage on a successful one.


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
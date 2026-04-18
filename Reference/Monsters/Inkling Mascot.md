---
type: pc
race: "Ooze"
class:
 - "Inkling Mascot"
subClass:
 - "CR 1/4"
cover: "Inkling Mascot.png"
campaign:
locations:
tags:
  - race/ooze
  - affinity/hostile
  - type/ooze
  - size/tiny
  - cr/1-4
  - source/scc
---
###### Inkling Mascot
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Inkling Mascot.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Tiny Ooze |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 18 (4d4 + 8) |
> | :FasUserGroup: Race | Ooze |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 14 | 6 | 7 | 11 |
| **Mod** | +0 | +3 | +2 | -2 | -2 | +0 |

**Speed:** 10 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** blindsight 60 ft., passive Perception 8
**Languages:** understands the languages of its creator but can't speak
**Skills:** Stealth +5
**Damage Immunities:** psychic
**Condition Immunities:** blinded; charmed; deafened; exhaustion; prone

---

### Traits

**Amorphous.** The inkling can move through a space as narrow as 1 inch wide without squeezing.


---

### Actions

**Blot.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) psychic damage.

**Ink Spray (1/Day).** The inkling sprays viscous ink at one creature within 15 feet of itself. The target must succeed on a DC 12 Constitution saving throw or be blinded until the end of the inkling's next turn.


---

### Bonus Actions

**Shadow Stealth.** While in dim light or darkness, the inkling takes the Hide action.


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
---
type: pc
race: "Beast"
class:
 - "Giant Insect"
subClass:
 - "CR —"
cover: "Giant Insect.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/large
  - cr/—
  - source/xphb
---
###### Giant Insect
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XPHB
___

> [!infobox|no-t right]
> ![[Giant Insect.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Large Beast |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC |  |
> | :FasHeart: HP | 30 + 10 for each spell level above 4 |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | XPHB |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 13 | 15 | 4 | 14 | 3 |
| **Mod** | +3 | +1 | +2 | -3 | +2 | -4 |

**Speed:** 40 ft., climb 40 ft., fly 40 ft. ((Wasp only)) &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 12
**Languages:** understands the languages you know

---

### Traits

**Spider Climb.** The insect can climb difficult surfaces, including along ceilings, without needing to make an ability check.


---

### Actions

**Multiattack.** The insect makes a number of attacks equal to half this spell's level (round down).

**Poison Jab.** m Bonus equals your spell attack modifier, reach 10 ft. *Hit:* 1d6 + 3 + summonSpellLevel Piercing damage plus 1d4 Poison damage.

**Web Bolt (Spider Only).** r Bonus equals your spell attack modifier, range 60 ft. *Hit:* 1d10 + 3 + summonSpellLevel Bludgeoning damage, and the target's Speed is reduced to 0 until the start of the insect's next turn.


---

### Bonus Actions

**Venomous Spew (Centipede Only).** con Your spell save DC, one creature the insect can see within 10 feet.  The target has the Poisoned condition until the start of the insect's next turn.


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
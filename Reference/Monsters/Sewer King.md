---
type: pc
race: "Fiend"
class:
 - "Sewer King"
subClass:
 - "CR 2"
cover: "Sewer King.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/2
  - source/mcv4ec
---
###### Sewer King
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV4EC
___

> [!infobox|no-t right]
> ![[Sewer King.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 52 (8d8 + 16) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | MCV4EC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 13 | 14 | 8 | 12 | 11 |
| **Mod** | +4 | +1 | +2 | -1 | +1 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** Infernal, telepathy 30 ft.
**Skills:** Perception +5, Stealth +3
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Beast Speech.** The sewer king can comprehend and verbally communicate with any Beast.


---

### Actions

**Rancid Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) piercing damage plus 7 (2d6) acid damage. If the target is a creature, it must succeed on a DC 12 Constitution saving throw or have the poisoned condition until the start of the sewer king's next turn.

**Summon Swarm (1/Day).** The sewer king chitters and summons a swarm of rats to its aid. The swarm appears in an unoccupied space within 30 feet of the sewer king that the sewer king can see. It acts as the sewer king's ally, obeys the sewer king's commands, and takes its turn immediately after the sewer king's. The swarm remains until it dies, the sewer king dies, or until the sewer king dismisses it as an action.


---

### Bonus Actions

**Skitter.** The sewer king moves up to its speed without provoking opportunity attacks.


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
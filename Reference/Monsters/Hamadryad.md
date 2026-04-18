---
type: pc
race: "Fey"
class:
 - "Hamadryad"
subClass:
 - "CR 2"
cover: "Hamadryad.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/2
  - source/mabjov
---
###### Hamadryad
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Hamadryad.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 13; 16 with barkskin |
> | :FasHeart: HP | 32 (5d8 + 10) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 14 | 14 | 10 | 15 |
| **Mod** | +0 | +3 | +2 | +2 | +0 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60ft., passive Perception 12
**Languages:** Sylvan
**Skills:** Perception +2, Stealth +6

---

### Traits

**Magic Resistance.** The hamadryad has advantage on saving throws against spells and other magical effects.

**Speak with Beasts and Plants.** The hamadryad can communicate with Beasts and Plants as if they shared a language.

**Tree Stride.** Once on her turn, the hamadryad can use 10 feet of her movement to step magically into one living tree within her reach and emerge from a second living tree within 60 feet of the first tree, appearing in an unoccupied space within 5 feet of the second tree. Both trees must be Large in size or bigger.


---

### Actions

**Multiattack.** The hamadryad makes two Claw attacks.

**Claw.** Melee Weapon Attack: +5 to hit, range 5 ft., one target. *Hit:* 5 (1d4 + 3) plus 10 (3d6) poison damage.


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
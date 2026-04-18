---
type: pc
race: "Ooze"
class:
 - "Psychic Gray Ooze"
subClass:
 - "CR 1"
cover: "Psychic Gray Ooze.png"
campaign:
locations:
tags:
  - race/ooze
  - affinity/hostile
  - type/ooze
  - size/medium
  - cr/1
  - source/xmm
---
###### Psychic Gray Ooze
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Psychic Gray Ooze.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Ooze |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 9 |
> | :FasHeart: HP | 37 (5d8 + 15) |
> | :FasUserGroup: Race | Ooze |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 8 | 16 | 10 | 6 | 2 |
| **Mod** | +1 | -1 | +3 | +0 | -2 | -4 |

**Speed:** 10 ft., climb 10 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., passive Perception 8
**Languages:** —
**Skills:** Stealth +3
**Damage Resistances:** acid; cold; fire; psychic
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; grappled; prone; restrained

---

### Traits

**Amorphous.** The ooze can move through a space as narrow as 1 inch without expending extra movement to do so.


---

### Actions

**Pseudopod.** m +3, reach 5 ft. *Hit:* 11 (3d6 + 1) Acid damage, and the target has Disadvantage on Intelligence saving throws until the end of the ooze's next turn.

**Psychic Crush.** int DC 10, one creature the ooze can see within 60 feet.  13 (3d8) Psychic damage.


---

### Reactions

**Mind Corrosion.**  The ooze fails a saving throw against a spell or another magical effect created by a creature.  The triggering creature takes 3 (1d6) Psychic damage.


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
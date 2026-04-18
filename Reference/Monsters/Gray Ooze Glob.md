---
type: pc
race: "Ooze"
class:
 - "Gray Ooze Glob"
subClass:
 - "CR 1/2"
cover: "Gray Ooze Glob.png"
campaign:
locations:
tags:
  - race/ooze
  - affinity/hostile
  - type/ooze
  - size/small
  - cr/1-2
  - source/hotb
---
###### Gray Ooze Glob
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: HotB
___

> [!infobox|no-t right]
> ![[Gray Ooze Glob.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Small Ooze |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 9 |
> | :FasHeart: HP | 19 (3d6 + 9) |
> | :FasUserGroup: Race | Ooze |
> | :FasBook: Source | HotB |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 6 | 16 | 1 | 6 | 2 |
| **Mod** | +1 | -2 | +3 | -5 | -2 | -4 |

**Speed:** 10 ft., climb 10 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., passive Perception 8
**Languages:** —
**Skills:** Stealth +2
**Damage Resistances:** acid; cold; fire
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; grappled; prone; restrained

---

### Traits

**Amorphous.** The ooze can move through a space as narrow as 1 inch without expending extra movement to do so.

**Corrosive Form.** Whenever a creature hits the ooze with a melee attack, that creature takes 2 Acid damage.


---

### Actions

**Pseudopod.** m +3, reach 5 ft. *Hit:* 10 (2d8 + 1) Acid damage.


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
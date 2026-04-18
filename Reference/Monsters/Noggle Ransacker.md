---
type: pc
race: "Fey"
class:
 - "Noggle Ransacker"
subClass:
 - "CR 1/4"
cover: "Noggle Ransacker.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/small
  - cr/1-4
  - source/lfl
---
###### Noggle Ransacker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: LFL
___

> [!infobox|no-t right]
> ![[Noggle Ransacker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Fey |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 13 (3d6 + 3) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | LFL |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 15 | 13 | 8 | 10 | 12 |
| **Mod** | +2 | +2 | +1 | -1 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** Common, Sylvan
**Skills:** Stealth +4

---

### Traits

**Siege Monster.** The noggle deals double damage to objects and structures.


---

### Actions

**Sabotaging Swipe.** m +4, reach 5 ft. *Hit:* 6 (1d8 + 2) Slashing damage. If the target is wearing armor, it is subjected to the following effect. dex DC 12.  The armor takes a -1 penalty to the AC it offers. The target can take an action to remove the penalty from its armor.


---

### Bonus Actions

**Nimble Escape.** The noggle takes the Disengage or Hide action.


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
---
type: pc
race: "Fey"
class:
 - "Bullywug Warrior"
subClass:
 - "CR 1/4"
cover: "Bullywug Warrior.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/1-4
  - source/xmm
---
###### Bullywug Warrior
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Bullywug Warrior.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 11 (2d8 + 2) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 14 | 13 | 7 | 10 | 7 |
| **Mod** | +1 | +2 | +1 | -2 | +0 | -2 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Bullywug, Common
**Skills:** Stealth +4

---

### Traits

**Amphibious.** The bullywug can breathe air and water.

**Speak with Frogs and Toads.** The bullywug can communicate simple concepts to frogs and toads when it speaks in Bullywug.


---

### Actions

**Insectile Rapier.** m +4, reach 5 ft. *Hit:* 6 (1d8 + 2) Piercing damage plus 2 (1d4) Poison damage.


---

### Bonus Actions

**Leap.** The bullywug can jump up to 30 feet by spending 10 feet of movement.


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
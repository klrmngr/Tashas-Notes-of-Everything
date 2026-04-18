---
type: pc
race: "Fey"
class:
 - "Bullywug Bog Sage"
subClass:
 - "CR 4"
cover: "Bullywug Bog Sage.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/4
  - source/xmm
---
###### Bullywug Bog Sage
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Bullywug Bog Sage.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 52 (8d8 + 16) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 16 | 14 | 10 | 16 | 12 |
| **Mod** | -1 | +3 | +2 | +0 | +3 | +1 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Bullywug, Common
**Saving Throws:** Con +4, Wis +5, Cha +3
**Skills:** Nature +4, Stealth +5

---

### Traits

**Amphibious.** The bullywug can breathe air and water.

**Speak with Frogs and Toads.** The bullywug can communicate simple concepts to frogs and toads when it speaks in Bullywug.


---

### Actions

**Multiattack.** The bullywug makes two Bog Staff attacks. It can replace any attack with a use of Spellcasting to cast Ray of Sickness.

**Bog Staff.** m +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Bludgeoning damage plus 10 (3d6) Poison damage.


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
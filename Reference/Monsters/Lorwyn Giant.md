---
type: pc
race: "Giant"
class:
 - "Lorwyn Giant"
subClass:
 - "CR 6"
cover: "Lorwyn Giant.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/6
  - source/lfl
---
###### Lorwyn Giant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: LFL
___

> [!infobox|no-t right]
> ![[Lorwyn Giant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 115 (11d12 + 44) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | LFL |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 13 | 18 | 9 | 16 | 8 |
| **Mod** | +5 | +1 | +4 | -1 | +3 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Giant
**Saving Throws:** Con +7, Wis +6

---

### Actions

**Multiattack.** The giant makes two attacks, using Stone Sword or Boulder in any combination.

**Stone Sword.** m +8, reach 15 ft. *Hit:* 21 (3d10 + 5) Slashing damage.

**Boulder.** r +8, range 60/240 ft. *Hit:* 14 (2d8 + 5) Bludgeoning damage. If the target is a Large or smaller creature, it has the Prone condition.


---

### Bonus Actions

**Name Sleep (Recharge 5–6).** The giant falls into a deep, restorative slumber. The giant gains 20 Temporary Hit Points and has the Unconscious condition until it takes damage or the end of its next turn. The giant has Advantage on ability checks and saving throws for 1 minute.


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
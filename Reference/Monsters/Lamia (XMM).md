---
type: pc
race: "Fiend"
class:
 - "Lamia"
subClass:
 - "CR 4"
cover: "Lamia.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/4
  - source/xmm
---
###### Lamia
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Lamia.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Fiend |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 97 (13d10 + 26) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 13 | 15 | 14 | 15 | 16 |
| **Mod** | +3 | +1 | +2 | +2 | +2 | +3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 12
**Languages:** Abyssal, Common
**Skills:** Deception +7, Insight +4, Stealth +5

---

### Actions

**Multiattack.** The lamia makes two Claw attacks. It can replace one attack with a use of Corrupting Touch.

**Claw.** m +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Slashing damage plus 7 (2d6) Psychic damage.

**Corrupting Touch.** wis DC 13, one creature the lamia can see within 5 feet.  13 (3d8) Psychic damage, and the target is cursed for 1 hour. Until the curse ends, the target has the Charmed and Poisoned conditions.


---

### Bonus Actions

**Leap.** The lamia jumps up to 30 feet by spending 10 feet of movement.


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
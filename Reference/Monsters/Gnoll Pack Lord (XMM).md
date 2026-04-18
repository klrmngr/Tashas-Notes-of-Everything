---
type: pc
race: "Fiend"
class:
 - "Gnoll Pack Lord"
subClass:
 - "CR 2"
cover: "Gnoll Pack Lord.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/2
  - source/xmm
---
###### Gnoll Pack Lord
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Gnoll Pack Lord.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 49 (9d8 + 9) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 13 | 8 | 11 | 9 |
| **Mod** | +3 | +2 | +1 | -1 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** Gnoll

---

### Actions

**Multiattack.** The gnoll makes two attacks, using Bone Whip or Bone Javelin in any combination, and it uses Incite Rampage if available.

**Bone Whip.** m +5, reach 10 ft. *Hit:* 8 (2d4 + 3) Slashing damage.

**Bone Javelin.** r +5, range 30/120 ft. *Hit:* 7 (1d8 + 3) Piercing damage.

**Incite Rampage (Recharge 5–6).** The gnoll targets another creature it can see within 60 feet of itself that has the Rampage Bonus Action. The target can take a Reaction to make one melee attack.


---

### Bonus Actions

**Rampage (2/Day).** Immediately after dealing damage to a creature that is already Bloodied, the gnoll moves up to half its Speed, and it makes one Bone Whip attack.


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
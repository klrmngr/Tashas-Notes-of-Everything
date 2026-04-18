---
type: pc
race: "Humanoid"
class:
 - "Scout Captain"
subClass:
 - "CR 3"
cover: "Scout Captain.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/3
  - source/xmm
---
###### Scout Captain
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Scout Captain.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 66 (12d8 + 12) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 16 | 12 | 14 | 15 | 11 |
| **Mod** | +0 | +3 | +1 | +2 | +2 | +0 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common plus one other language
**Saving Throws:** Dex +5, Int +4
**Skills:** Perception +6, Stealth +7, Survival +6

---

### Actions

**Multiattack.** The scout makes two attacks, using Shortsword or Longbow in any combination.

**Shortsword.** m +5, reach 5 ft. *Hit:* 6 (1d6 + 3) Piercing damage, plus 10 (3d6) Piercing damage if the attack was made with Advantage.

**Longbow.** r +5, range 150/600 ft. *Hit:* 7 (1d8 + 3) Piercing damage, plus 10 (3d6) Piercing damage if the attack was made with Advantage.


---

### Bonus Actions

**Aim.** The scout has Advantage on the next attack roll it makes during the current turn.


---

### Reactions

**Uncanny Dodge.**  The scout is hit by an attack roll.  The scout halves the damage (round down) it takes from that attack.


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
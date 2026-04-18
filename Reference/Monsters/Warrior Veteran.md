---
type: pc
race: "Humanoid"
class:
 - "Warrior Veteran"
subClass:
 - "CR 3"
cover: "Warrior Veteran.png"
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
###### Warrior Veteran
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Warrior Veteran.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 65 (10d8 + 20) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 13 | 14 | 10 | 11 | 10 |
| **Mod** | +3 | +1 | +2 | +0 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common plus one other language
**Skills:** Athletics +5, Perception +2

---

### Actions

**Multiattack.** The warrior makes two Greatsword or Heavy Crossbow attacks.

**Greatsword.** m +5, reach 5 ft. *Hit:* 10 (2d6 + 3) Slashing damage.

**Heavy Crossbow.** r +3, range 100/400 ft. *Hit:* 12 (2d10 + 1) Piercing damage.


---

### Reactions

**Parry.**  The warrior is hit by a melee attack roll while holding a weapon.  The warrior adds 2 to its AC against that attack, possibly causing it to miss.


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
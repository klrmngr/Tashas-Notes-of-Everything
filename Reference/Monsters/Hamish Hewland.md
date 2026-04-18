---
type: pc
race: "Giant"
class:
 - "Hamish Hewland"
subClass:
 - "CR 5"
cover: "Hamish Hewland.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/5
  - source/aitfr-dn
---
###### Hamish Hewland
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: AitFR-DN
___

> [!infobox|no-t right]
> ![[Hamish Hewland.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 85 (10d12 + 20) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | AitFR-DN |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 11 | 15 | 10 | 14 | 10 |
| **Mod** | +6 | +0 | +2 | +0 | +2 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common, Dwarvish, Giant
**Saving Throws:** Str +9, Wis +5
**Skills:** Athletics +9, History +3, Insight +5, Perception +5

---

### Actions

**Multiattack.** Hamish makes two attacks with his axe or throws two rocks.

**Axe.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 17 (2d10 + 6) slashing damage.

**Rock.** Ranged Weapon Attack: +9 to hit, range 60/240 ft., one target. *Hit:* 17 (2d10 + 6) bludgeoning damage.


---

### Reactions

**Parry.** Hamish adds 2 to his AC against one melee attack that would hit him. To do so, he must see the attacker and be wielding a melee weapon or a shield.


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
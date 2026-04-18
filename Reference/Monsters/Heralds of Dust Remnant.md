---
type: pc
race: "Humanoid"
class:
 - "Heralds of Dust Remnant"
subClass:
 - "CR 4"
cover: "Heralds of Dust Remnant.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/4
  - source/mpp
---
###### Heralds of Dust Remnant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Heralds of Dust Remnant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 45 (7d8 + 14) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 14 | 15 | 17 | 14 | 11 |
| **Mod** | -1 | +2 | +2 | +3 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Common plus three more languages
**Skills:** Arcana +5, Perception +4, Stealth +6
**Damage Resistances:** necrotic

---

### Actions

**Multiattack.** The remnant makes two Necrotic Surge attacks.

**Necrotic Surge.** Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 120 ft., one target. *Hit:* 14 (2d10 + 3) necrotic damage.


---

### Bonus Actions

**Phase (2/Day).** The remnant becomes partially incorporeal for as long as it maintains concentration on the effect (as if concentrating on a spell). While partially incorporeal, the remnant has resistance to bludgeoning, piercing, and slashing damage.


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
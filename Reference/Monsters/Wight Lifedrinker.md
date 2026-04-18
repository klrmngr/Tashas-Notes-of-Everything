---
type: pc
race: "Undead"
class:
 - "Wight Lifedrinker"
subClass:
 - "CR 3"
cover: "Wight Lifedrinker.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/3
  - source/hotb
---
###### Wight Lifedrinker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: HotB
___

> [!infobox|no-t right]
> ![[Wight Lifedrinker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 82 (11d8 + 33) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | HotB |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 14 | 16 | 10 | 13 | 15 |
| **Mod** | +2 | +2 | +3 | +0 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 13
**Languages:** Common plus one other language
**Skills:** Perception +3, Stealth +4
**Damage Resistances:** necrotic
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Sunlight Sensitivity.** While in sunlight, the wight has Disadvantage on ability checks and attack rolls.


---

### Actions

**Multiattack.** The wight makes two attacks, using Necrotic Sword or Necrotic Bow in any combination. It can replace one attack with a use of Drink Life.

**Necrotic Sword.** m +4, reach 5 ft. *Hit:* 6 (1d8 + 2) Slashing damage plus 4 (1d8) Necrotic damage.

**Necrotic Bow.** r +4, range 150/600 ft. *Hit:* 6 (1d8 + 2) Piercing damage plus 4 (1d8) Necrotic damage.

**Drink Life (Recharge 5–6).** con DC 13, one creature within 5 feet.  6 (1d8 + 2) Necrotic damage, and the wight regains a number of Hit Points equal to the Necrotic damage taken.


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
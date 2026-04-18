---
type: pc
race: "Giant"
class:
 - "Frost Giant"
subClass:
 - "CR 8"
cover: "Frost Giant.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/8
  - source/xmm
---
###### Frost Giant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Frost Giant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 149 (13d12 + 65) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 9 | 21 | 9 | 10 | 12 |
| **Mod** | +6 | -1 | +5 | -1 | +0 | +1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Giant
**Saving Throws:** Con +8, Wis +3, Cha +4
**Skills:** Athletics +9, Perception +3
**Damage Immunities:** cold

---

### Actions

**Multiattack.** The giant makes two attacks, using Frost Axe or Great Bow in any combination.

**Frost Axe.** m +9, reach 10 ft. *Hit:* 19 (2d12 + 6) Slashing damage plus 9 (2d8) Cold damage.

**Great Bow.** r +9, range 150/600 ft. *Hit:* 17 (2d10 + 6) Piercing damage plus 7 (2d6) Cold damage, and the target's Speed decreases by 10 feet until the end of its next turn.


---

### Bonus Actions

**War Cry (Recharge 5–6).** The giant or one creature of its choice that can see or hear it gains 16 (2d10 + 5) Temporary Hit Points and has Advantage on attack rolls until the start of the giant's next turn.


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
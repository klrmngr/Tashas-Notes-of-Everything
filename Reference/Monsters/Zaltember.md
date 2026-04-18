---
type: pc
race: "Giant"
class:
 - "Zaltember"
subClass:
 - "CR 1"
cover: "Zaltember.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/large
  - cr/1
  - source/skt
---
###### Zaltember
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Zaltember.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Large Giant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 13 (chain shirt) |
> | :FasHeart: HP | 30 (4d10 + 8) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 10 | 14 | 10 | 10 | 10 |
| **Mod** | +3 | +0 | +2 | +0 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common, Giant
**Damage Immunities:** fire

---

### Actions

**Battleaxe.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 12 (2d8 + 3) slashing damage, or 14 (2d10 + 3) slashing damage if used with two hands.

**Javelin.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 10 (2d6 + 3) piercing damage.


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
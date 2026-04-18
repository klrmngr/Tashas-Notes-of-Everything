---
type: pc
race: "Undead"
class:
 - "Gloam"
subClass:
 - "CR 0"
cover: "Gloam.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/tiny
  - cr/0
  - source/wbtw
---
###### Gloam
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Gloam.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Tiny Undead |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 2 (1d4) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 3 | 15 | 10 | 3 | 12 | 7 |
| **Mod** | -4 | +2 | +0 | -4 | +1 | -2 |

**Speed:** 40 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** —
**Skills:** Perception +3, Stealth +4
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Keen Smell.** The cat has advantage on Wisdom (Perception) checks that rely on smell.


---

### Actions

**Claws.** Melee Weapon Attack: +0 to hit, reach 5 ft., one target. *Hit:* 1 slashing damage.

**Cloud of Dust.** On its first turn in combat or when it is reduced to 0 hit points, the cat expels a cloud of dust that acts as dust of sneezing and choking


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
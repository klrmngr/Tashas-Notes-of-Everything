---
type: pc
race: "Construct"
class:
 - "Scaladar"
subClass:
 - "CR 8"
cover: "Scaladar.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/huge
  - cr/8
  - source/wdmm
---
###### Scaladar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDMM
___

> [!infobox|no-t right]
> ![[Scaladar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Huge Construct |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 94 (7d12 + 49) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | WDMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 10 | 25 | 1 | 12 | 1 |
| **Mod** | +4 | +0 | +7 | -5 | +1 | -5 |

**Speed:** 30 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** —
**Damage Resistances:** fire; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** force; lightning; poison
**Condition Immunities:** charmed; paralyzed; poisoned

---

### Traits

**Lightning Absorption.** Whenever the scaladar is subjected to lightning damage, it takes no damage, and its sting deals an extra 11 (2d10) lightning damage until the end of its next turn.

**Scaladar Link.** The scaladar knows the location of other scaladar within 100 feet of it, and it can sense when any of them take damage.


---

### Actions

**Multiattack.** The scaladar makes three attacks: two with its claws and one with its sting.

**Claw.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 10 (1d12 + 4) bludgeoning damage, and the target is grappled (escape DC 15). The scaladar has two claws, each of which can grapple one target.

**Sting.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 9 (1d10 + 4) piercing damage plus 11 (2d10) lightning damage.


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
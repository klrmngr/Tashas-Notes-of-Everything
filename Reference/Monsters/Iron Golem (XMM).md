---
type: pc
race: "Construct"
class:
 - "Iron Golem"
subClass:
 - "CR 16"
cover: "Iron Golem.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/16
  - source/xmm
---
###### Iron Golem
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Iron Golem.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 20 |
> | :FasHeart: HP | 252 (24d10 + 120) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 9 | 20 | 3 | 11 | 1 |
| **Mod** | +7 | -1 | +5 | -4 | +0 | -5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 10
**Languages:** understands Common plus two other languages but can't speak
**Damage Immunities:** fire; poison; psychic
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Fire Absorption.** Whenever the golem is subjected to Fire damage, it regains a number of Hit Points equal to the Fire damage dealt.

**Immutable Form.** The golem can't shape-shift.

**Magic Resistance.** The golem has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The golem makes two attacks, using Bladed Arm or Fiery Bolt in any combination.

**Bladed Arm.** m +12, reach 10 ft. *Hit:* 20 (3d8 + 7) Slashing damage plus 10 (3d6) Fire damage.

**Fiery Bolt.** r +10, range 120 ft. *Hit:* 36 (8d8) Fire damage.

**Poison Breath (Recharge 6).** con DC 18, each creature in a 60-foot Cone.  55 (10d10) Poison damage.  Half damage.


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
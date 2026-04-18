---
type: pc
race: "Undead"
class:
 - "Storm Giant Skeleton"
subClass:
 - "CR 16"
cover: "Storm Giant Skeleton.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/huge
  - cr/16
  - source/cm
---
###### Storm Giant Skeleton
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Candlekeep Mysteries
___

> [!infobox|no-t right]
> ![[Storm Giant Skeleton.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Huge Undead |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 13 (armor scraps) |
> | :FasHeart: HP | 204 (24d12 + 48) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Candlekeep Mysteries |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 29 | 14 | 15 | 3 | 8 | 1 |
| **Mod** | +9 | +2 | +2 | -4 | -1 | -5 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** —
**Saving Throws:** Str +14, Con +7
**Skills:** Perception +4
**Damage Vulnerabilities:** bludgeoning
**Damage Resistances:** cold
**Damage Immunities:** lightning; poison; thunder
**Condition Immunities:** exhaustion; poisoned

---

### Actions

**Multiattack.** The giant makes two attacks with its greatsword or hurls two rocks.

**Greatsword.** Melee Weapon Attack: +14 to hit, reach 10 ft., one target. *Hit:* 30 (6d6 + 9) slashing damage plus 18 (4d8) necrotic damage.

**Rock.** Ranged Weapon Attack: +14 to hit, reach 60/240 ft., one target. *Hit:* 35 (4d12 + 9) bludgeoning damage.

**Lightning Strike (Recharge 5–6).** The giant hurls a magical lightning bolt at a point it can see within 500 feet of it. Each creature within 10 feet of that point must make a DC 15 Dexterity saving throw, taking 54 (12d8) lightning damage on a failed save, or half as much damage on a successful one.


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
---
type: pc
race: "Monstrosity"
class:
 - "Deep Crow"
subClass:
 - "CR 9"
cover: "Deep Crow.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/9
  - source/ai
---
###### Deep Crow
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Acquisitions Incorporated
___

> [!infobox|no-t right]
> ![[Deep Crow.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 133 (14d10 + 56) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Acquisitions Incorporated |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 16 | 18 | 8 | 15 | 14 |
| **Mod** | +5 | +3 | +4 | -1 | +2 | +2 |

**Speed:** 20 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 120 ft., passive Perception 16
**Languages:** Deep Crow
**Saving Throws:** Con +8, Wis +6
**Skills:** Perception +6, Stealth +11

---

### Traits

**Magic Resistance.** The deep crow has advantage on saving throws against spells and other magical effects.

**Shadow Stealth.** While in dim light or darkness, the deep crow can take the Hide action as a bonus action.

**Sunlight Sensitivity.** While in sunlight, the deep crow has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** The deep crow makes three attacks: one with its mandibles and two with its claws.

**Mandibles.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 16 (2d10 + 5) piercing damage, and the target is grappled (escape DC 17). Until this grapple ends, the target is restrained, and the deep crow can't use its mandibles on another target.

**Claw.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) slashing damage.


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
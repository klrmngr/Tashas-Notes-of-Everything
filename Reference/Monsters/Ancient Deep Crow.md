---
type: pc
race: "Monstrosity"
class:
 - "Ancient Deep Crow"
subClass:
 - "CR 15"
cover: "Ancient Deep Crow.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/huge
  - cr/15
  - source/ai
---
###### Ancient Deep Crow
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Acquisitions Incorporated
___

> [!infobox|no-t right]
> ![[Ancient Deep Crow.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Huge Monstrosity |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 187 (15d12 + 90) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Acquisitions Incorporated |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 16 | 23 | 10 | 15 | 19 |
| **Mod** | +6 | +3 | +6 | +0 | +2 | +4 |

**Speed:** 20 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 120 ft., passive Perception 17
**Languages:** Deep Crow
**Saving Throws:** Con +11, Wis +7
**Skills:** Perception +7, Stealth +13
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks

---

### Traits

**Magic Resistance.** The ancient deep crow has advantage on saving throws against spells and other magical effects.

**Shadow Stealth.** While in dim light or darkness, the ancient deep crow can take the Hide action as a bonus action.


---

### Actions

**Multiattack.** The ancient deep crow makes three attacks: one with its mandibles and two with its claws.

**Mandibles.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 17 (2d10 + 6) piercing damage, and the target is grappled (escape DC 19). Until this grapple ends, the target is restrained, and the ancient deep crow can't use its mandibles on another target.

**Claw.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 13 (2d6 + 6) slashing damage.

**Shadow Caw.** The ancient deep crow releases an ear-splitting caw. Each creature within 60 feet of the crow and able to hear it must make a DC 17 Constitution saving throw. On a failure, a creature takes 10 (3d6) psychic damage.


---

### Legendary Actions

### 

**Detect.** The deep crow makes a Wisdom (Perception) check.

**Shadow Caw (Costs 2 Actions).** The ancient deep crow uses Shadow Caw.

**Wing Attack (Costs 2 Actions).** The ancient deep crow beats its wings. Each creature within 10 feet of the deep crow must succeed on a DC 19 Dexterity saving throw or take 13 (2d6 + 6) bludgeoning damage and be knocked prone. The ancient deep crow can then fly up to half its flying speed.


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
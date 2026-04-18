---
type: pc
race: "Monstrosity"
class:
 - "Peryton"
subClass:
 - "CR 2"
cover: "Peryton.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/2
  - source/mm
---
###### Peryton
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Peryton.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 12 | 13 | 9 | 12 | 10 |
| **Mod** | +3 | +1 | +1 | -1 | +1 | +0 |

**Speed:** 20 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** understands Common and Elvish but can't speak
**Skills:** Perception +5
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks

---

### Traits

**Dive Attack.** If the peryton is flying and dives at least 30 feet straight toward a target and then hits it with a melee weapon attack, the attack deals an extra 9 (2d8) damage to the target.

**Flyby.** The peryton doesn't provoke an opportunity attack when it flies out of an enemy's reach.

**Keen Sight and Smell.** The peryton has advantage on Wisdom (Perception) checks that rely on sight or smell.


---

### Actions

**Multiattack.** The peryton makes one gore attack and one talon attack.

**Gore.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage.

**Talons.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 8 (2d4 + 3) piercing damage.


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
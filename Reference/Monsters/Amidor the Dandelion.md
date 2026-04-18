---
type: pc
race: "Plant"
class:
 - "Amidor the Dandelion"
subClass:
 - "CR 1/2"
cover: "Amidor the Dandelion.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/small
  - cr/1-2
  - source/wbtw
---
###### Amidor the Dandelion
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Amidor the Dandelion.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Small Plant |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 28 (8d6) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 15 | 10 | 13 | 12 | 17 |
| **Mod** | -2 | +2 | +0 | +1 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Sylvan
**Saving Throws:** Str +0, Dex +4, Con +2, Wis +3
**Skills:** Perception +3, Persuasion +5, Stealth +4

---

### Traits

**Speak with Beasts and Plants.** Amidor can communicate with Beasts and Plants as if it shared a language with them.


---

### Actions

**Rapier.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) piercing damage.

**Seed Sling.** Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. *Hit:* 4 (1d4 + 2) bludgeoning damage.


---

### Reactions

**Parry.** Amidor adds 2 to its AC against one melee attack that would hit it. To do so, Amidor must see the attacker and be wielding a melee weapon.


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
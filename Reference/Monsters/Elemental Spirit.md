---
type: pc
race: "Elemental"
class:
 - "Elemental Spirit"
subClass:
 - "CR —"
cover: "Elemental Spirit.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/medium
  - cr/—
  - source/tce
---
###### Elemental Spirit
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tasha's Cauldron of Everything
___

> [!infobox|no-t right]
> ![[Elemental Spirit.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Elemental |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC |  |
> | :FasHeart: HP | 50 + 10 for each spell level above 4th |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | Tasha's Cauldron of Everything |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 17 | 4 | 10 | 16 |
| **Mod** | +4 | +2 | +3 | -3 | +0 | +3 |

**Speed:** 40 ft., burrow 40 ft. ((earth only)), fly 40 ft. ((air only; hover)) (hover), swim 40 ft. ((water only)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Primordial, understands the languages you speak
**Damage Resistances:** lightning, thunder (Air only); piercing, slashing (Earth only); acid (Water only)
**Damage Immunities:** poison; fire (Fire only)
**Condition Immunities:** exhaustion; paralyzed; petrified; poisoned; unconscious

---

### Traits

**Amorphous Form (Air, Fire, and Water Only).** The elemental can move through a space as narrow as 1 inch wide without squeezing.


---

### Actions

**Multiattack.** The elemental makes a number of attacks equal to half this spell's level (rounded down).

**Slam.** Melee Weapon Attack:  to hit, reach 5 ft., one target. *Hit:* 1d10 + 4 + summonSpellLevel bludgeoning damage (Air, Earth, and Water only) or fire damage (Fire only).


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
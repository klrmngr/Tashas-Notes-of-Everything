---
type: pc
race: "Monstrosity"
class:
 - "Draconian Foot Soldier"
subClass:
 - "CR 1/2"
cover: "Draconian Foot Soldier.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/1-2
  - source/ftd
---
###### Draconian Foot Soldier
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Draconian Foot Soldier.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 22 (4d8 + 4) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 11 | 13 | 8 | 8 | 10 |
| **Mod** | +1 | +0 | +1 | -1 | -1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 9
**Languages:** Common, Draconic

---

### Traits

**Controlled Fall.** When the draconian falls and isn't incapacitated, it subtracts up to 100 feet from the fall when calculating the fall's damage.

**Death Throes.** When the draconian is reduced to 0 hit points, its body turns to stone and releases a petrifying gas. Each creature within 5 feet of the draconian must succeed on a DC 11 Constitution saving throw or be restrained as it begins to turn to stone. The restrained creature must repeat the saving throw at the end of its next turn. On a success, the effect ends; otherwise the creature is petrified for 1 minute. After 1 minute, the body of the draconian crumbles to dust.


---

### Actions

**Multiattack.** The draconian makes two Shortsword attacks.

**Shortsword.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 4 (1d6 + 1) piercing damage.


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
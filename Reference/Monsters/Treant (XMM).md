---
type: pc
race: "Plant"
class:
 - "Treant"
subClass:
 - "CR 9"
cover: "Treant.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/huge
  - cr/9
  - source/xmm
---
###### Treant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Treant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Huge Plant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 138 (12d12 + 60) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 8 | 21 | 12 | 16 | 12 |
| **Mod** | +6 | -1 | +5 | +1 | +3 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Druidic, Elvish, Sylvan
**Damage Vulnerabilities:** fire
**Damage Resistances:** bludgeoning; piercing

---

### Traits

**Siege Monster.** The treant deals double damage to objects and structures.


---

### Actions

**Multiattack.** The treant makes two Slam attacks.

**Slam.** m +10, reach 5 ft. *Hit:* 16 (3d6 + 6) Bludgeoning damage.

**Hail of Bark.** r +10, range 180 ft. *Hit:* 28 (4d10 + 6) Piercing damage.

**Animate Trees (1/Day).** The treant magically animates up to two trees it can see within 60 feet of itself. Each tree uses the Treant stat block, except it has Intelligence and Charisma scores of 1, it can't speak, and it lacks this action. The tree takes its turn immediately after the treant on the same Initiative count, and it obeys the treant. A tree remains animate for 1 day or until it dies, the treant dies, or it is more than 120 feet from the treant. The tree then takes root if possible.


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
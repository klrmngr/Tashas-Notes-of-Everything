---
type: pc
race: "Plant"
class:
 - "Hook Horror Spore Servant"
subClass:
 - "CR 3"
cover: "Hook Horror Spore Servant.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/medium
  - cr/3
  - source/oota
---
###### Hook Horror Spore Servant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Out of the Abyss
___

> [!infobox|no-t right]
> ![[Hook Horror Spore Servant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Plant |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 75 (10d10 + 10) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | Out of the Abyss |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 10 | 15 | 2 | 6 | 1 |
| **Mod** | +4 | +0 | +2 | -4 | -2 | -5 |

**Speed:** 20 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft. (blind beyond this radius), passive Perception 8
**Languages:** —
**Damage Resistances:** poison
**Condition Immunities:** blinded; charmed; frightened; paralyzed

---

### Actions

**Multiattack.** The spore servant makes two hook attacks.

**Hook.** Melee Weapon Attack: +6 to hit, reach 10 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage.


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
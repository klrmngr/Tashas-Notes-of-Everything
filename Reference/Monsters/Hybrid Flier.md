---
type: pc
race: "Humanoid (simic hybrid)"
class:
 - "Hybrid Flier"
subClass:
 - "CR 2"
cover: "Hybrid Flier.png"
campaign:
locations:
tags:
  - race/simic hybrid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/ggr
---
###### Hybrid Flier
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Hybrid Flier.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (simic hybrid) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 39 (6d8 + 12) |
> | :FasUserGroup: Race | Humanoid (simic hybrid) |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 16 | 14 | 11 | 10 | 11 |
| **Mod** | +1 | +3 | +2 | +0 | +0 | +0 |

**Speed:** 30 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common plus any one language
**Damage Resistances:** acid

---

### Actions

**Multiattack.** The hybrid makes two javelin attacks. It can replace one javelin attack with Spit Acid.

**Javelin.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.

**Spit Acid.** Ranged Weapon Attack: +5 to hit, range 20/60 ft., one target. *Hit:* 10 (4d4) acid damage.


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
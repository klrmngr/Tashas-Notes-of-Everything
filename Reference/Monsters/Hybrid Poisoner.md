---
type: pc
race: "Humanoid (simic hybrid)"
class:
 - "Hybrid Poisoner"
subClass:
 - "CR 1"
cover: "Hybrid Poisoner.png"
campaign:
locations:
tags:
  - race/simic hybrid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/ggr
---
###### Hybrid Poisoner
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Hybrid Poisoner.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (simic hybrid) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 26 (4d8 + 8) |
> | :FasUserGroup: Race | Humanoid (simic hybrid) |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 19 | 14 | 12 | 13 | 12 |
| **Mod** | +1 | +4 | +2 | +1 | +1 | +1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 30 ft., passive Perception 13
**Languages:** Common plus any one language
**Saving Throws:** Dex +6, Con +4
**Skills:** Athletics +3, Perception +3, Stealth +6
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Assassinate.** During its first turn, the hybrid poisoner has advantage on attack rolls against any creature that hasn't taken a turn. Any hit the hybrid scores against a surprised creature is a critical hit.

**Poisonous Skin.** Any creature that touches the hybrid or hits it with a melee attack while within 5 feet of it takes 3 (1d6) poison damage.


---

### Actions

**Toxic Touch.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (2d6) bludgeoning damage, and the target must succeed on a DC 12 Constitution saving throw or become poisoned for 1 minute. At the end of each of the poisoned target's turns, it must repeat the save, taking 3 (1d6) poison damage on a failed save, or ending the effect on itself on a successful one.


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
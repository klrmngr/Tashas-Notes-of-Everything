---
type: pc
race: "Humanoid (lava child)"
class:
 - "Lava Child"
subClass:
 - "CR 3"
cover: "Lava Child.png"
campaign:
locations:
tags:
  - race/lava child
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/wdmm
---
###### Lava Child
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDMM
___

> [!infobox|no-t right]
> ![[Lava Child.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (lava child) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 60 (8d8 + 24) |
> | :FasUserGroup: Race | Humanoid (lava child) |
> | :FasBook: Source | WDMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 13 | 16 | 11 | 10 | 10 |
| **Mod** | +4 | +1 | +3 | +0 | +0 | +0 |

**Speed:** 25 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, Ignan
**Skills:** Athletics +6, Survival +2
**Damage Immunities:** fire; bludgeoning, piercing, slashing from metal weapons

---

### Traits

**Metal Immunity.** The lava child can move through metal without hindrance, and it has advantage on attack rolls against any creature wearing metal armor or using a metal shield.


---

### Actions

**Multiattack.** The lava child makes two attacks: one with its bite and one with its claws.

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage.

**Claws.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) slashing damage.


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
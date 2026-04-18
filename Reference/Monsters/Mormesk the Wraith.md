---
type: pc
race: "Undead"
class:
 - "Mormesk the Wraith"
subClass:
 - "CR 3"
cover: "Mormesk the Wraith.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/3
  - source/lmop
---
###### Mormesk the Wraith
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Lost Mine of Phandelver
___

> [!infobox|no-t right]
> ![[Mormesk the Wraith.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 45 (6d8 + 18) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Lost Mine of Phandelver |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 16 | 16 | 12 | 14 | 15 |
| **Mod** | -2 | +3 | +3 | +1 | +2 | +2 |

**Speed:** 0 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Common, Infernal
**Damage Resistances:** acid; cold; fire; lightning; thunder; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** necrotic; poison
**Condition Immunities:** charmed; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Incorporeal Movement.** The wraith can move through an object or another creature, but can't stop there.

**Sunlight Sensitivity.** While in sunlight, the wraith has disadvantage on attack rolls and on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Life Drain.** Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. *Hit:* 16 (3d8 + 3) necrotic damage, and the target must succeed on a DC 13 Constitution saving throw or its hit point maximum is reduced by an amount equal to the damage taken. If this attack reduces the target's hit point maximum to 0, the target dies. This reduction to the target's hit point maximum lasts until the target finishes a long rest.


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
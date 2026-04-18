---
type: pc
race: "Undead"
class:
 - "Naergoth Bladelord"
subClass:
 - "CR 11"
cover: "Naergoth Bladelord.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/11
  - source/rot
---
###### Naergoth Bladelord
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Rise of Tiamat
___

> [!infobox|no-t right]
> ![[Naergoth Bladelord.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 135 (18d8 + 54) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Rise of Tiamat |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 12 | 16 | 12 | 14 | 16 |
| **Mod** | +5 | +1 | +3 | +1 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 16
**Languages:** Common, Draconic
**Saving Throws:** Dex +5, Wis +6
**Skills:** Perception +6, Stealth +5
**Damage Resistances:** necrotic; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Sunlight Sensitivity.** While in sunlight, Naergoth has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** Naergoth makes three attacks, either with his longsword or longbow. He can use Life Drain in place of one longsword attack.

**Life Drain.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 20 (5d6 + 3) necrotic damage. The target must succeed on a DC 15 Constitution saving throw or its hit point maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.

**Longsword.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 9 (1d8 + 5) slashing damage, or 10 (1d10 + 5) if used with two hands, plus 10 (3d6) necrotic damage.

**Longbow.** Ranged Weapon Attack: +5 to hit, range 150/600 ft., one target. *Hit:* 5 (1d8 + 1) piercing damage plus 10 (3d6) necrotic damage.


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
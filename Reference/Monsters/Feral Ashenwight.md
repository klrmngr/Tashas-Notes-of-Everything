---
type: pc
race: "Undead"
class:
 - "Feral Ashenwight"
subClass:
 - "CR 5"
cover: "Feral Ashenwight.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/5
  - source/pabtso
---
###### Feral Ashenwight
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Phandelver and Below: The Shattered Obelisk
___

> [!infobox|no-t right]
> ![[Feral Ashenwight.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 65 (10d8 + 20) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Phandelver and Below: The Shattered Obelisk |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 13 | 15 | 4 | 14 | 6 |
| **Mod** | +4 | +1 | +2 | -3 | +2 | -2 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 12
**Languages:** understands the languages it knew in life but can't speak
**Saving Throws:** Str +7, Con +5
**Damage Resistances:** necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned; unconscious

---

### Actions

**Multiattack.** The ashenwight makes two Necrotic Shard attacks.

**Necrotic Shard.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 7 (1d6 + 4) necrotic damage. If the target is a creature, it has disadvantage on the next attack roll it makes before the end of its next turn.


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
---
type: pc
race: "Humanoid (elf)"
class:
 - "Raezil"
subClass:
 - "CR 1"
cover: "Raezil.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/wbtw
---
###### Raezil
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Raezil.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral or Neutral |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 27 (6d8) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 15 | 10 | 12 | 14 | 16 |
| **Mod** | +0 | +2 | +0 | +1 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 16
**Languages:** Common, Elvish
**Skills:** Deception +5, Insight +4, Investigation +5, Perception +6, Persuasion +5, Sleight Of Hand +4, Stealth +4

---

### Traits

**Cunning Action.** On each of her turns, Raezil can use a bonus action to take the Dash, Disengage, or Hide action.

**Fey Ancestry.** Raezil has advantage on saving throws against being charmed, and magic can't put her to sleep.

**Sneak Attack (1/Turn).** Raezil deals an extra 7 (2d6) damage when she hits a target with a weapon attack and has advantage on the attack roll, or when the target is within 5 feet of an ally of hers that isn't incapacitated and Raezil doesn't have disadvantage on the attack roll.


---

### Actions

**Multiattack.** Raezil makes two melee attacks.

**Shortsword.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.

**Hand Crossbow.** Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.


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
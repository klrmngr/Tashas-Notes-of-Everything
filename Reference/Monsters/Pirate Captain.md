---
type: pc
race: "Humanoid (any race)"
class:
 - "Pirate Captain"
subClass:
 - "CR 2"
cover: "Pirate Captain.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/gos
---
###### Pirate Captain
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Pirate Captain.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 14 (studded leather) |
> | :FasHeart: HP | 45 (7d8 + 14) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 14 | 11 | 10 | 14 |
| **Mod** | +3 | +2 | +2 | +0 | +0 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** any one language (usually Common)
**Skills:** Athletics +5, Intimidation +4

---

### Traits

**Flourish.** The captain adds its Charisma modifier to the damage roll for its longsword attacks (included in the attack).

**Sea Legs.** The captain has advantage on ability checks and saving throws to resist being knocked prone.


---

### Actions

**Multiattack.** The captain makes two attacks: one with its hand crossbow and one with its longsword.

**Hand Crossbow.** Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.

**Longsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 9 (1d8 + 5) slashing damage, or 10 (1d10 + 5) slashing damage if used with two hands.


---

### Reactions

**Shape Up, Ye Dog (2/Day).** Whenever a friendly creature within 30 feet of the captain that can hear it misses with an attack, the captain can yell perilous threats to allow that creature to reroll the attack roll.


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
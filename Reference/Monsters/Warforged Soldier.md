---
type: pc
race: "Humanoid (warforged)"
class:
 - "Warforged Soldier"
subClass:
 - "CR 1"
cover: "Warforged Soldier.png"
campaign:
locations:
tags:
  - race/warforged
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/erlw
---
###### Warforged Soldier
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Warforged Soldier.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (warforged) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (natural armor, shield) |
> | :FasHeart: HP | 30 (4d8 + 12) |
> | :FasUserGroup: Race | Humanoid (warforged) |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 12 | 16 | 10 | 14 | 11 |
| **Mod** | +3 | +1 | +3 | +0 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Common
**Skills:** Athletics +5, Perception +4, Survival +4
**Damage Resistances:** poison
**Condition Immunities:** disease

---

### Traits

**Warforged Resilience.** The warforged has advantage on saving throws against being poisoned and is immune to disease. Magic can't put it to sleep.


---

### Actions

**Multiattack.** The warforged makes two armblade attacks.

**Armblade.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage.

**Javelin.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.


---

### Reactions

**Protection.** When an attacker the warforged can see makes an attack roll against a creature within 5 feet of the warforged, the warforged can impose disadvantage on the attack roll.


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
---
type: pc
race: "Humanoid (elf)"
class:
 - "Vulkoori Venom Priest"
subClass:
 - "CR 2"
cover: "Vulkoori Venom Priest.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/efa
---
###### Vulkoori Venom Priest
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: EFA
___

> [!infobox|no-t right]
> ![[Vulkoori Venom Priest.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 44 (8d8 + 8) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | EFA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 16 | 12 | 10 | 16 | 13 |
| **Mod** | +2 | +3 | +1 | +0 | +3 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 15
**Languages:** Common, Elvish, Giant
**Saving Throws:** Con +3, Wis +5
**Skills:** Perception +5, Religion +2, Stealth +5
**Damage Resistances:** poison

---

### Traits

**Fey Ancestry.** Magic can't put the priest to sleep.


---

### Actions

**Venom Staff.** m +4, reach 5 ft. *Hit:* 9 (2d6 + 2) Bludgeoning damage, and the target has the Poisoned condition until the end of the priest's next turn.


---

### Bonus Actions

**Intensify Poison.** Each creature with the Poisoned condition within a 30-foot Emanation originating from the priest takes 3 (1d6) Poison damage.


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
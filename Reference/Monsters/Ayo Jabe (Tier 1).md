---
type: pc
race: "Humanoid (ranger, genasi)"
class:
 - "Ayo Jabe (Tier 1)"
subClass:
 - "CR 3"
cover: "Ayo Jabe (Tier 1).png"
campaign:
locations:
tags:
  - race/ranger
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/crcotn
---
###### Ayo Jabe (Tier 1)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Ayo Jabe (Tier 1).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (ranger, genasi) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 14 (studded leather) |
> | :FasHeart: HP | 65 (10d8 + 20) |
> | :FasUserGroup: Race | Humanoid (ranger, genasi) |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 14 | 14 | 10 | 12 | 12 |
| **Mod** | +2 | +2 | +2 | +0 | +1 | +1 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Goblin, Orc
**Saving Throws:** Str +4, Dex +4
**Skills:** Athletics +4, Perception +3, Survival +3
**Damage Resistances:** acid

---

### Traits

**Amphibious.** Ayo can breathe air and water.


---

### Actions

**Multiattack.** Ayo makes two Harpoon or Longbow attacks.

**Harpoon.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 11 (2d8 + 2) piercing damage.

**Longbow.** Ranged Weapon Attack: +4 to hit, range 150/600 ft., one target. *Hit:* 11 (2d8 + 2) piercing damage.


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
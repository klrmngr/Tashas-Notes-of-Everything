---
type: pc
race: "Humanoid (ranger, genasi)"
class:
 - "Ayo Jabe (Tier 2)"
subClass:
 - "CR 5"
cover: "Ayo Jabe (Tier 2).png"
campaign:
locations:
tags:
  - race/ranger
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/crcotn
---
###### Ayo Jabe (Tier 2)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Ayo Jabe (Tier 2).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (ranger, genasi) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 15 (studded leather) |
> | :FasHeart: HP | 97 (15d8 + 30) |
> | :FasUserGroup: Race | Humanoid (ranger, genasi) |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 16 | 14 | 10 | 14 | 12 |
| **Mod** | +2 | +3 | +2 | +0 | +2 | +1 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common, Goblin, Orc
**Saving Throws:** Str +5, Dex +6
**Skills:** Athletics +5, Perception +5, Survival +5
**Damage Resistances:** acid

---

### Traits

**Amphibious.** Ayo can breathe air and water.


---

### Actions

**Multiattack.** Ayo makes three Harpoon or Longbow attacks.

**Harpoon.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 11 (2d8 + 2) piercing damage.

**Longbow.** Ranged Weapon Attack: +6 to hit, range 150/600 ft., one target. *Hit:* 12 (2d8 + 3) piercing damage.


---

### Bonus Actions

**Reposition.** Ayo issues orders to one ally she can see within 30 feet of herself. If the target can see or hear Ayo, it can spend its reaction to move up to its speed. This movement doesn't provoke opportunity attacks.


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
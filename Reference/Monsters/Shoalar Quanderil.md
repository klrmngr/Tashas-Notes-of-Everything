---
type: pc
race: "Humanoid (genasi)"
class:
 - "Shoalar Quanderil"
subClass:
 - "CR 4"
cover: "Shoalar Quanderil.png"
campaign:
locations:
tags:
  - race/genasi
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/4
  - source/lr
---
###### Shoalar Quanderil
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: LR
___

> [!infobox|no-t right]
> ![[Shoalar Quanderil.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (genasi) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 11; 14 with mage armor |
> | :FasHeart: HP | 75 (10d8 + 30) |
> | :FasUserGroup: Race | Humanoid (genasi) |
> | :FasBook: Source | LR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 12 | 16 | 14 | 10 | 18 |
| **Mod** | +1 | +1 | +3 | +2 | +0 | +4 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Aquan, Common
**Skills:** Arcana +6, Deception +8, Insight +4, Persuasion +8
**Damage Resistances:** acid; lightning; thunder

---

### Traits

**Amphibious.** Shoalar can breathe air and water.


---

### Actions

**Dagger.** Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or ranged 20/60 ft., one target. *Hit:* 3 (1d4 + 1) piercing damage.


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
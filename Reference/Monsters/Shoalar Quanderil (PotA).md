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
  - source/pota
---
###### Shoalar Quanderil
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Princes of the Apocalypse
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
> | :FasShield: AC | 10; 13 with mage armor |
> | :FasHeart: HP | 60 (8d8 + 24) |
> | :FasUserGroup: Race | Humanoid (genasi) |
> | :FasBook: Source | Princes of the Apocalypse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 12 | 16 | 14 | 10 | 17 |
| **Mod** | +0 | +1 | +3 | +2 | +0 | +3 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Aquan, Common
**Skills:** Arcana +4, Deception +5, Insight +2, Persuasion +5
**Damage Resistances:** acid

---

### Traits

**Amphibious.** Shoalar can breathe air and water.


---

### Actions

**Dagger.** Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or ranged 20/60 ft., one target. *Hit:* 3 (1d4 + 1) piercing damage.


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
---
type: pc
race: "Elemental"
class:
 - "Xorn"
subClass:
 - "CR 5"
cover: "Xorn.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/medium
  - cr/5
  - source/xmm
---
###### Xorn
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Xorn.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Elemental |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 19 |
> | :FasHeart: HP | 84 (8d8 + 48) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 10 | 22 | 11 | 10 | 11 |
| **Mod** | +3 | +0 | +6 | +0 | +0 | +0 |

**Speed:** 20 ft., burrow 20 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., Tremorsense 60 ft., passive Perception 16
**Languages:** Primordial (Terran)
**Skills:** Perception +6, Stealth +6
**Damage Immunities:** poison
**Condition Immunities:** paralyzed; petrified; poisoned

---

### Traits

**Earth Glide.** The xorn can burrow through nonmagical, unworked earth and stone. While doing so, the xorn doesn't disturb the material it moves through.

**Treasure Sense.** The xorn can pinpoint the location of precious metals and stones within 60 feet of itself.


---

### Actions

**Multiattack.** The xorn makes one Bite attack and three Claw attacks.

**Bite.** m +6, reach 5 ft. *Hit:* 17 (4d6 + 3) Piercing damage.

**Claw.** m +6, reach 5 ft. *Hit:* 8 (1d10 + 3) Slashing damage.


---

### Bonus Actions

**Charge.** The xorn moves up to its Speed or Burrow Speed straight toward an enemy it can sense.


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
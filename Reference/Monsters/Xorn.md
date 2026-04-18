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
  - source/mm
---
###### Xorn
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
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
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 73 (7d8 + 42) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 10 | 22 | 11 | 10 | 11 |
| **Mod** | +3 | +0 | +6 | +0 | +0 | +0 |

**Speed:** 20 ft., burrow 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., tremorsense 60 ft., passive Perception 16
**Languages:** Terran
**Skills:** Perception +6, Stealth +3
**Damage Resistances:** piercing, slashing from nonmagical attacks that aren't adamantine

---

### Traits

**Earth Glide.** The xorn can burrow through nonmagical, unworked earth and stone. While doing so, the xorn doesn't disturb the material it moves through.

**Stone Camouflage.** The xorn has advantage on Dexterity (Stealth) checks made to hide in rocky terrain.

**Treasure Sense.** The xorn can pinpoint, by scent, the location of precious metals and stones, such as coins and gems, within 60 feet of it.


---

### Actions

**Multiattack.** The xorn makes three claw attacks and one bite attack.

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 13 (3d6 + 3) piercing damage.

**Claw.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage.


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
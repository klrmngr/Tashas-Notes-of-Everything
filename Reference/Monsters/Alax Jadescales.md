---
type: pc
race: "Humanoid (dragonborn)"
class:
 - "Alax Jadescales"
subClass:
 - "CR 2"
cover: "Alax Jadescales.png"
campaign:
locations:
tags:
  - race/dragonborn
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/lrdt
---
###### Alax Jadescales
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: LRDT
___

> [!infobox|no-t right]
> ![[Alax Jadescales.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dragonborn) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 58 (9d8 + 18) |
> | :FasUserGroup: Race | Humanoid (dragonborn) |
> | :FasBook: Source | LRDT |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 10 | 14 | 11 | 16 | 15 |
| **Mod** | +0 | +0 | +2 | +0 | +3 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Draconic
**Skills:** Animal Handling +5, Survival +5
**Damage Resistances:** poison

---

### Actions

**Multiattack.** Alax makes two Fire Strike attacks.

**Fire Strike.** Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 10 (2d6 + 3) fire damage.

**Breath Weapon (Recharges after a Short or Long Rest).** Alax exhales a 15-foot cone of fire. Each creature in that area must make a DC 12 Dexterity saving throw, taking 14 (4d6) fire damage on a failed save, or half as much damage on a successful one.


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
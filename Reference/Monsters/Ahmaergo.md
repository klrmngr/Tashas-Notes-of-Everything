---
type: pc
race: "Humanoid (dwarf)"
class:
 - "Ahmaergo"
subClass:
 - "CR 9"
cover: "Ahmaergo.png"
campaign:
locations:
tags:
  - race/dwarf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/wdh
---
###### Ahmaergo
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Ahmaergo.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dwarf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 143 (22d8 + 44) |
> | :FasUserGroup: Race | Humanoid (dwarf) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 15 | 14 | 15 | 14 | 12 |
| **Mod** | +5 | +2 | +2 | +2 | +2 | +1 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 16
**Languages:** Common, Dwarvish, Undercommon
**Saving Throws:** Str +9, Con +6
**Skills:** Athletics +9, Intimidation +5, Perception +6
**Damage Resistances:** poison

---

### Traits

**Dwarven Resilience.** Ahmaergo has advantage on saving throws against being poisoned.

**Indomitable (2/Day).** Ahmaergo can reroll a saving throw that he fails. He must use the new roll.

**Second Wind (Recharges after a Short or Long Rest).** As a bonus action, Ahmaergo can regain 20 hit points.

**Extra Damage.** If Ahmaergo has more than half his hit points remaining he deals an extra 7 (2d6) slashing damage on every hit.


---

### Actions

**Multiattack.** Ahmaergo makes three attacks with his greataxe.

**Greataxe.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 11 (1d12 + 5) slashing damage.

**Heavy Crossbow.** Ranged Weapon Attack: +6 to hit, range 100/400 ft., one target. *Hit:* 7 (1d10 + 2) piercing damage.


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
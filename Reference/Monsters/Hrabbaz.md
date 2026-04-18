---
type: pc
race: "Humanoid (half-orc)"
class:
 - "Hrabbaz"
subClass:
 - "CR 5"
cover: "Hrabbaz.png"
campaign:
locations:
tags:
  - race/half-orc
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/wdh
---
###### Hrabbaz
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Hrabbaz.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (half-orc) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 112 (15d8 + 45) |
> | :FasUserGroup: Race | Humanoid (half-orc) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 15 | 17 | 10 | 14 | 12 |
| **Mod** | +5 | +2 | +3 | +0 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** Common, Orc
**Saving Throws:** Str +8, Con +6
**Skills:** Athletics +8, Intimidation +4, Perception +5

---

### Traits

**Indomitable (2/Day).** Hrabbaz can reroll a saving throw that he fails. He must use the new roll.

**Relentless Endurance (Recharges after a Long Rest).** When Hrabbaz is reduced to 0 hit points but not killed outright, he drops to 1 hit point instead.

**Extra Damage.** As long as Hrabbaz has more than half his hit points left he deals an extra 3 (1d6) damage on all hits.


---

### Actions

**Multiattack.** Hrabbaz makes three attacks with his morningstar.

**Morningstar.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 9 (1d8 + 5) piercing damage.


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
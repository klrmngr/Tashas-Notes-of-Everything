---
type: pc
race: "Humanoid (gnome)"
class:
 - "Skeemo Weirdbottle"
subClass:
 - "CR 6"
cover: "Skeemo Weirdbottle.png"
campaign:
locations:
tags:
  - race/gnome
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/6
  - source/wdh
---
###### Skeemo Weirdbottle
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Skeemo Weirdbottle.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Small Humanoid (gnome) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 72 (16d6 + 16) |
> | :FasUserGroup: Race | Humanoid (gnome) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 14 | 12 | 17 | 12 | 15 |
| **Mod** | -1 | +2 | +1 | +3 | +1 | +2 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Abyssal, Common, Gnomish, Undercommon
**Saving Throws:** Int +6, Wis +4
**Skills:** Arcana +6, History +6, Perception +4, Performance +5

---

### Traits

**Gnome Cunning.** Skeemo has advantage on Intelligence, Wisdom, and Charisma saving throws against magic.


---

### Actions

**Dagger.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage. Or Ranged Weapon Attack: +5 to hit, range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.


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
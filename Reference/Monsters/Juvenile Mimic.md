---
type: pc
race: "Monstrosity (shapechanger)"
class:
 - "Juvenile Mimic"
subClass:
 - "CR 0"
cover: "Juvenile Mimic.png"
campaign:
locations:
tags:
  - race/shapechanger
  - affinity/hostile
  - type/monstrosity
  - size/tiny
  - cr/0
  - source/tce
---
###### Juvenile Mimic
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tasha's Cauldron of Everything
___

> [!infobox|no-t right]
> ![[Juvenile Mimic.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Tiny Monstrosity (shapechanger) |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 7 (2d4 + 2) |
> | :FasUserGroup: Race | Monstrosity (shapechanger) |
> | :FasBook: Source | Tasha's Cauldron of Everything |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 12 | 13 | 10 | 13 | 10 |
| **Mod** | -5 | +1 | +1 | +0 | +1 | +0 |

**Speed:** 10 ft., climb 10 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Common, Undercommon, telepathy 120 ft.
**Skills:** Stealth +3
**Damage Immunities:** acid
**Condition Immunities:** prone

---

### Traits

**False Appearance (Object Form Only).** While the mimic remains motionless, it is indistinguishable from an ordinary object.

**Spider Climb.** The mimic can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Bite.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 1 piercing damage plus 2 (1d4) acid damage.

**Shape-Shift.** The mimic polymorphs into an object or back into its true, amorphous form. Its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies.


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
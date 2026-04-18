---
type: pc
race: "Humanoid (human)"
class:
 - "Frost Druid"
subClass:
 - "CR 5"
cover: "Frost Druid.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/idrotf
---
###### Frost Druid
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Frost Druid.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 13 (hide armor) |
> | :FasHeart: HP | 67 (9d8 + 27) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 13 | 16 | 10 | 16 | 9 |
| **Mod** | +1 | +1 | +3 | +0 | +3 | -1 |

**Speed:** 40 ft., burrow 5 ft. ((fox form only)), climb 30 ft. ((goat form only)), fly 60 ft. ((owl form only)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft. (beast form only), passive Perception 16
**Languages:** Common, Druidic
**Saving Throws:** Int +3, Wis +6
**Skills:** Nature +3, Perception +6, Survival +6
**Damage Resistances:** cold

---

### Actions

**Multiattack.** The druid makes two melee attacks.

**Ice Sickle (Humanoid Form Only).** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 3 (1d4 + 1) slashing damage plus 5 (2d4) cold damage.

**Maul (Beast Form Only).** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 3 (1d4 + 1) piercing damage.

**Change Shape.** The druid magically polymorphs into a beast form—fox, mountain goat, owl, or wolf—or back into its humanoid form. Any equipment it is wearing or carrying is absorbed or borne by the beast form (the druid's choice). It reverts to its humanoid form when it dies. The druid's statistics are the same in each form, except where noted in this stat block.


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
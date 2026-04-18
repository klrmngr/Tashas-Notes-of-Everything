---
type: pc
race: "Humanoid (any race)"
class:
 - "Warlock of the Fiend"
subClass:
 - "CR 7"
cover: "Warlock of the Fiend.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/7
  - source/vgm
---
###### Warlock of the Fiend
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Warlock of the Fiend.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 78 (12d8 + 24) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 15 | 12 | 12 | 18 |
| **Mod** | +0 | +2 | +2 | +1 | +1 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** any two languages (usually Abyssal or Infernal)
**Saving Throws:** Wis +4, Cha +7
**Skills:** Arcana +4, Deception +7, Persuasion +7, Religion +4
**Damage Resistances:** slashing from nonmagical attacks not made with silvered weapons

---

### Traits

**Dark One's Own Luck (Recharges after a Short or Long Rest).** When the warlock makes an ability check or saving throw, it can add a d10 to the roll. It can do this after the roll is made but before any of the roll's effects occur.


---

### Actions

**Mace.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d6) bludgeoning damage plus 10 (3d6) fire damage.


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
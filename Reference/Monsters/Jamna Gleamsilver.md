---
type: pc
race: "Humanoid (gnome)"
class:
 - "Jamna Gleamsilver"
subClass:
 - "CR 1"
cover: "Jamna Gleamsilver.png"
campaign:
locations:
tags:
  - race/gnome
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1
  - source/hotdq
---
###### Jamna Gleamsilver
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Hoard of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Jamna Gleamsilver.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Small Humanoid (gnome) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 (leather armor) |
> | :FasHeart: HP | 22 (4d6 + 8) |
> | :FasUserGroup: Race | Humanoid (gnome) |
> | :FasBook: Source | Hoard of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 17 | 14 | 15 | 10 | 12 |
| **Mod** | -1 | +3 | +2 | +2 | +0 | +1 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Common, Gnomish, Goblin, Sylvan
**Saving Throws:** Dex +5, Int +4
**Skills:** Acrobatics +5, Deception +3, Insight +2, Perception +4, Persuasion +3, Stealth +7

---

### Traits

**Cunning Action.** Jamna can take a bonus action to take the Dash, Disengage, or Hide action.

**Gnome Cunning.** Jamna has advantage on Intelligence, Wisdom and Charisma saving throws against magic.


---

### Actions

**Multiattack.** Jamna attacks twice with her shortswords.

**Shortsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage, or 9 (1d6 + 3) plus (1d6) piercing damage if the target is Medium or larger.


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
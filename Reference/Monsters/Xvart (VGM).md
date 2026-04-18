---
type: pc
race: "Humanoid (xvart)"
class:
 - "Xvart"
subClass:
 - "CR 1/8"
cover: "Xvart.png"
campaign:
locations:
tags:
  - race/xvart
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1-8
  - source/vgm
---
###### Xvart
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Xvart.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Small Humanoid (xvart) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 (leather armor) |
> | :FasHeart: HP | 7 (2d6) |
> | :FasUserGroup: Race | Humanoid (xvart) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 14 | 10 | 8 | 7 | 7 |
| **Mod** | -1 | +2 | +0 | -1 | -2 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 30 ft., passive Perception 8
**Languages:** Abyssal
**Skills:** Stealth +4

---

### Traits

**Low Cunning.** The xvart can take the Disengage action as a bonus action on each of its turns.

**Overbearing Pack.** The xvart has advantage on Strength (Athletics) checks to shove a creature if at least one of the xvart's allies is within 5 feet of the target and the ally isn't incapacitated.

**Raxivort's Tongue.** The xvart can communicate with ordinary bats and rats, as well as giant bats and giant rats.


---

### Actions

**Shortsword.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.

**Sling.** Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. *Hit:* 4 (1d4 + 2) bludgeoning damage.


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
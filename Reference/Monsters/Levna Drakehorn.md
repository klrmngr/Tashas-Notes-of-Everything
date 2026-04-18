---
type: pc
race: "Humanoid (human)"
class:
 - "Levna Drakehorn"
subClass:
 - "CR —"
cover: "Levna Drakehorn.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/—
  - source/dsotdq
---
###### Levna Drakehorn
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Dragonlance: Shadow of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Levna Drakehorn.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 18 (plate) |
> | :FasHeart: HP | 13 (2d8 + 4) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Dragonlance: Shadow of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 10 | 14 | 10 | 11 | 14 |
| **Mod** | +2 | +0 | +2 | +0 | +0 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common
**Saving Throws:** Con +4
**Skills:** Athletics +4, Intimidation +4, Perception +2

---

### Traits

**Bonus Proficiencies.** Levna is proficient with simple and martial weapons, shields, and all armor.

**Pack Tactics.** Levna has advantage on an attack roll against a creature if at least one of her allies is within 5 feet of the creature and the ally isn't incapacitated.


---

### Actions

**Greatsword.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 9 (2d6 + 2) slashing damage.


---

### Reactions

**Protection.** When a creature Levna can see within 5 feet of her is targeted by an attack, she can impose disadvantage on the attack roll if she can see the attacker and she is wielding a melee weapon.


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
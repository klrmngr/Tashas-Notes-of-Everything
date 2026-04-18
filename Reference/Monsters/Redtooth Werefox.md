---
type: pc
race: "Monstrosity (elf)"
class:
 - "Redtooth Werefox"
subClass:
 - "CR 3"
cover: "Redtooth Werefox.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/3
  - source/mcv4ec
---
###### Redtooth Werefox
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV4EC
___

> [!infobox|no-t right]
> ![[Redtooth Werefox.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Monstrosity (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 60 (11d8 + 11) |
> | :FasUserGroup: Race | Monstrosity (elf) |
> | :FasBook: Source | MCV4EC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 17 | 12 | 11 | 13 | 10 |
| **Mod** | +3 | +3 | +1 | +0 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** Common, Elvish (can't speak in fox form)
**Skills:** Acrobatics +5, Perception +5, Survival +3

---

### Actions

**Multiattack.** The werefox makes two Bite attacks, two Lance attacks, or one Bite attack and one Lance attack.

**Bite (Fox or Hybrid Form Only).** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 8 (1d10 + 3) piercing damage. If the werefox moved at least 20 feet straight toward the target immediately before the hit and the target is a Medium or smaller creature, the target must succeed on a DC 13 Strength saving throw or have the prone condition.

**Lance (Elf or Hybrid Form Only).** Melee Weapon Attack: +5 to hit, reach 10 ft., one target. *Hit:* 9 (1d12 + 3) piercing damage.

**Entangling Arrow (Elf or Hybrid Form Only).** Ranged Weapon Attack: +5 to hit, range 150/600 ft., one target. *Hit:* 10 (2d6 + 3) piercing damage, and the target must succeed on a DC 11 Dexterity saving throw or have the restrained condition until the start of the werefox's next turn.


---

### Bonus Actions

**Change Shape.** The werefox polymorphs into a fox-elf hybrid, into a fox, or back into its elf form. Its game statistics, other than its speed, are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its elf form if it dies.

**Vulpine Nimbleness (Fox or Hybrid Form Only).** The werefox takes the Dash or Disengage action.


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
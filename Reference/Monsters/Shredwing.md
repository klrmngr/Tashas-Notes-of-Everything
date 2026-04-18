---
type: pc
race: "Fiend"
class:
 - "Shredwing"
subClass:
 - "CR 12"
cover: "Shredwing.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/12
  - source/coa
---
###### Shredwing
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Shredwing.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 21 (natural armor) |
> | :FasHeart: HP | 170 (20d8 + 80) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 19 | 19 | 15 | 16 | 11 |
| **Mod** | +0 | +4 | +4 | +2 | +3 | +0 |

**Speed:** 0 ft., fly 60 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 21
**Languages:** —
**Saving Throws:** Dex +8, Con +8
**Skills:** Acrobatics +8, Athletics +4, Perception +11, Survival +7
**Damage Resistances:** cold; fire; poison; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Condition Immunities:** blinded; charmed; poisoned

---

### Traits

**Merged.** After using the Burrow ability, if the shredwing is merged with another creature, any damage dealt to the shredwing is split evenly between it and the merged creature.


---

### Actions

**Multiattack.** The shredwing makes three Talon attacks.

**Talon.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage plus 7 (2d6) poison damage.

**Burrow (Recharge 5–6).** On a hit, the creature takes an additional 32 (5d12) slashing damage as the wings merge with it. While merged, the creature moves with the shredwing, takes 19 (3d12) necrotic damage at the start of each of its turn, and has the grappled condition. The shredwing can unmerge at any time, leaving the creature and dropping it if airborne. The only other way to end the merge is to kill the shredwing.
If the merged creature dies while merged, the shredwing permanently takes over its body. It gains the merged creature's hit dice, natural armor, possessions, and languages. If any of the merged creature's statistics are higher than the shredwing, it inherits those statistics as well. A creature permanently merged by the shredwing can only be resurrected through a Wish spell or similar.


---

### Bonus Actions

**Aggressive.** The shredwing can move up to its speed toward a hostile creature that it can see.


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
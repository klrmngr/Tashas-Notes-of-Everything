---
type: pc
race: "Elemental"
class:
 - "Khargra"
subClass:
 - "CR 1/8"
cover: "Khargra.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/small
  - cr/1-8
  - source/mff
---
###### Khargra
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MFF
___

> [!infobox|no-t right]
> ![[Khargra.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Small Elemental |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 11 (2d6 + 4) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | MFF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 10 | 14 | 5 | 11 | 6 |
| **Mod** | +1 | +0 | +2 | -3 | +0 | -2 |

**Speed:** 5 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Terran
**Skills:** Perception +2, Stealth +2

---

### Traits

**Iron Scent.** The khargra can scent the location of ferrous metal within 30 feet of it.


---

### Actions

**Bite.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d4 + 1) piercing damage, and if the target is wearing metal armor or carrying a metal shield, the khargra attaches to that armor or shield. While attached, the khargra doesn't attack. Instead, at the start of each of the khargra's turns, roll a d20. On a 10 or higher, the armor or shield takes a permanent and cumulative -1 penalty to the AC it offers. Armor reduced to an AC of 10 or a shield that drops to a +0 bonus is destroyed.
The khargra can detach itself by spending 5 feet of its movement. A creature, including the target, can use its action to detach the khargra.

**Earth Phasing.** Until the end of its next turn, the khargra can fly through nonmagical earth and stone. While doing so, it doesn't disturb the material it moves through. It can end its movement within earth or stone, but if it remains within earth or stone when this ability ends, it takes 14 (4d6) force damage and immediately moves to the nearest unoccupied space.


---

### Reactions

**Opportunistic Hunger.** When a creature the khargra can see within 5 feet of it hits it with a metal weapon, the khargra can make a bite attack against that creature.


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
---
type: pc
race: "Elemental"
class:
 - "Frost Salamander"
subClass:
 - "CR 9"
cover: "Frost Salamander.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/huge
  - cr/9
  - source/mpmm
---
###### Frost Salamander
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Frost Salamander.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Huge Elemental |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 168 (16d12 + 64) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 12 | 18 | 7 | 11 | 7 |
| **Mod** | +5 | +1 | +4 | -2 | +0 | -2 |

**Speed:** 60 ft., burrow 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., tremorsense 60 ft., passive Perception 14
**Languages:** Primordial
**Saving Throws:** Con +8, Wis +4
**Skills:** Perception +4
**Damage Vulnerabilities:** fire
**Damage Immunities:** cold

---

### Traits

**Burning Fury.** When the salamander takes fire damage, its Freezing Breath automatically recharges.


---

### Actions

**Multiattack.** The salamander makes one Bite attack and four Claw attacks.

**Bite.** Melee Weapon Attack: +9 to hit, reach 15 ft., one target. *Hit:* 9 (1d8 + 5) piercing damage plus 5 (1d10) cold damage.

**Claw.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 8 (1d6 + 5) piercing damage.

**Freezing Breath (Recharge 6).** The salamander exhales chill wind in a 60-foot cone. Each creature in that area must make a DC 17 Constitution saving throw, taking 44 (8d10) cold damage on a failed save, or half as much damage on a successful one.


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
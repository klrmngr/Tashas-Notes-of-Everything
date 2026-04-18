---
type: pc
race: "Elemental"
class:
 - "Salamander"
subClass:
 - "CR 5"
cover: "Salamander.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/5
  - source/mm
---
###### Salamander
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Salamander.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Elemental |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 90 (12d10 + 24) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 15 | 11 | 10 | 12 |
| **Mod** | +4 | +2 | +2 | +0 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Ignan
**Damage Vulnerabilities:** cold
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** fire

---

### Traits

**Heated Body.** A creature that touches the salamander or hits it with a melee attack while within 5 feet of it takes 7 (2d6) fire damage.

**Heated Weapons.** Any metal melee weapon the salamander wields deals an extra 3 (1d6) fire damage on a hit (included in the attack).


---

### Actions

**Multiattack.** The salamander makes two attacks: one with its spear and one with its tail.

**Spear.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage, or 13 (2d8 + 4) piercing damage if used with two hands to make a melee attack, plus 3 (1d6) fire damage.

**Tail.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 11 (2d6 + 4) bludgeoning damage plus 7 (2d6) fire damage, and the target is grappled (escape DC 14). Until this grapple ends, the target is restrained, the salamander can automatically hit the target with its tail, and the salamander can't make tail attacks against other targets.


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
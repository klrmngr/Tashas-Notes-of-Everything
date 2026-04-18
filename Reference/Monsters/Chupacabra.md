---
type: pc
race: "Monstrosity"
class:
 - "Chupacabra"
subClass:
 - "CR 3"
cover: "Chupacabra.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/3
  - source/psx
---
###### Chupacabra
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: PSX
___

> [!infobox|no-t right]
> ![[Chupacabra.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 45 (6d8 + 18) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | PSX |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 14 | 16 | 6 | 13 | 9 |
| **Mod** | +2 | +2 | +3 | -2 | +1 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 13
**Languages:** —
**Skills:** Perception +3, Stealth +4
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical weapons

---

### Traits

**Sunlight Sensitivity.** While in sunlight, the chupacabra has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 7 (2d4 + 2) piercing damage. If the target is a creature, it must succeed on a DC 13 Strength saving throw or be knocked prone.

**Drain Blood.** Melee Weapon Attack: +4 to hit, reach 5 ft., one creature that is prone, incapacitated, or restrained. *Hit:* 5 (1d6 + 2) necrotic damage. The target must succeed on a DC 13 Constitution saving throw or its hit point maximum is reduced by an amount equal to the damage taken, and the chupacabra regains hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.


---

### Reactions

**Pin.** If a creature within 5 feet of the chupacabra stands up, the chupacabra can use its reaction to make a bite attack.


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
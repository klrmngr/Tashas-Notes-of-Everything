---
type: pc
race: "Elemental"
class:
 - "Tempest Hart"
subClass:
 - "CR 11"
cover: "Tempest Hart.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/huge
  - cr/11
  - source/mcv4ec
---
###### Tempest Hart
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV4EC
___

> [!infobox|no-t right]
> ![[Tempest Hart.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Huge Elemental |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 147 (14d12 + 56) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | MCV4EC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 17 | 18 | 3 | 18 | 14 |
| **Mod** | +5 | +3 | +4 | -4 | +4 | +2 |

**Speed:** 50 ft., fly 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 22
**Languages:** —
**Saving Throws:** Dex +7, Wis +8
**Skills:** Perception +12
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** lightning; thunder
**Condition Immunities:** exhaustion

---

### Traits

**Legendary Resistance (3/Day).** If the hart fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The hart makes a Lightning Antlers attack and a Thunder Hooves attack.

**Lightning Antlers.** Melee Weapon Attack: +9 to hit, reach 15 ft., one target. *Hit:* 16 (2d10 + 5) lightning damage. If the target is a creature, it must succeed on a DC 16 Constitution saving throw or have the stunned condition until the start of the hart's next turn.

**Thunder Hooves.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 14 (2d8 + 5) thunder damage.


---

### Reactions

**Entangling Growth.** Immediately after a creature the hart can see within 120 feet of itself hits it with an attack roll, the hart reduces the damage to itself by half. The attacker must immediately make a DC 16 Strength saving throw as beanstalks coil around it in its space. On a failed save, the creature has the grappled condition (escape DC 16) and has the restrained condition as long as it is grappled. The beanstalks vanish after 1 minute, if the hart has the incapacitated condition, or when the hart dies.

**Lightning Call.** In response to making a saving throw, the hart calls down a bolt of lightning that targets a creature it can see within 120 feet of itself. The target must make a DC 16 Dexterity saving throw, taking 19 (3d12) lightning damage on a failed save, or half as much damage on a successful one.


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
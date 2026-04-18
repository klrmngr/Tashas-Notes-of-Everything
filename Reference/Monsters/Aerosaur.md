---
type: pc
race: "Monstrosity (dinosaur)"
class:
 - "Aerosaur"
subClass:
 - "CR 10"
cover: "Aerosaur.png"
campaign:
locations:
tags:
  - race/dinosaur
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/10
  - source/bgg
---
###### Aerosaur
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Aerosaur.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity (dinosaur) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 155 (10d20 + 50) |
> | :FasUserGroup: Race | Monstrosity (dinosaur) |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 10 | 21 | 3 | 10 | 5 |
| **Mod** | +8 | +0 | +5 | -4 | +0 | -3 |

**Speed:** 20 ft., fly 120 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** —
**Skills:** Perception +4

---

### Traits

**Magic Resistance.** The aerosaur has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The aerosaur makes one Bite attack and one Talons attack.

**Bite.** Melee Weapon Attack: +12 to hit, reach 10 ft., one target. *Hit:* 27 (3d12 + 8) piercing damage. If the target is a Huge or smaller creature, it has the grappled condition (escape DC 18). Until this grapple ends, the target has the restrained condition, and the aerosaur can't Bite another target.

**Talons.** Melee Weapon Attack: +12 to hit, reach 10 ft., one target. *Hit:* 24 (3d10 + 8) slashing damage.

**Wing Gusts (Recharge 5–6).** The aerosaur beats its wings, creating bursts of thunderous force. Each creature within 10 feet of the aerosaur must make a DC 20 Strength saving throw. On a failed save, a creature takes 38 (7d10) thunder damage, is pushed up to 30 feet horizontally from the aerosaur, and has the prone condition. On a successful save, a creature takes half as much damage and is pushed up to 15 feet horizontally from the aerosaur.


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
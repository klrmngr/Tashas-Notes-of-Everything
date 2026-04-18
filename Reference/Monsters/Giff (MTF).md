---
type: pc
race: "Humanoid"
class:
 - "Giff"
subClass:
 - "CR 3"
cover: "Giff.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/mtf
---
###### Giff
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Giff.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 16 (breastplate) |
> | :FasHeart: HP | 60 (8d8 + 24) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 17 | 11 | 12 | 12 |
| **Mod** | +4 | +2 | +3 | +0 | +1 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common

---

### Traits

**Headfirst Charge.** The giff can try to knock a creature over; if the giff moves at least 20 feet in a straight line that ends within 5 feet of a Large or smaller creature, that creature must succeed on a DC 14 Strength saving throw or take 7 (2d6) bludgeoning damage and be knocked prone.

**Firearms Knowledge.** The giff's mastery of its weapons enables it to ignore the loading property of muskets and pistols.


---

### Actions

**Multiattack.** The giff makes two pistol attacks.

**Longsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with two hands.

**Musket.** Ranged Weapon Attack: +4 to hit, range 40/120 ft., one target. *Hit:* 8 (1d12 + 2) piercing damage.

**Pistol.** Ranged Weapon Attack: +4 to hit, range 30/90 ft., one target. *Hit:* 7 (1d10 + 2) piercing damage.

**Fragmentation Grenade (1/Day).** The giff throws a grenade up to 60 feet. Each creature within 20 feet of the grenade's detonation must make a DC 15 Dexterity saving throw, taking 17 (5d6) piercing damage on a failed save, or half as much damage on a successful one.


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
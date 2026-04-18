---
type: pc
race: "Construct"
class:
 - "Warforged Titan"
subClass:
 - "CR 8"
cover: "Warforged Titan.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/huge
  - cr/8
  - source/erlw
---
###### Warforged Titan
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Warforged Titan.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Huge Construct |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 125 (10d12 + 60) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 8 | 22 | 3 | 11 | 1 |
| **Mod** | +6 | -1 | +6 | -4 | +0 | -5 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** understands the languages of its creator but can't speak
**Damage Immunities:** poison; psychic
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Platforms.** The warforged titan has two platforms built into its chassis. One Medium or smaller creature can ride on each platform without squeezing. To make a melee attack against a target within 5 feet of the warforged, they must use spears or weapons with reach and the target must be Large or larger.

**Siege Monster.** The warforged titan deals double damage to objects and structures.


---

### Actions

**Multiattack.** The warforged titan makes one axehand attack and one hammerfist attack.

**Axehand.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 19 (3d8 + 6) slashing damage, plus 11 (2d10) slashing damage if the target is prone.

**Hammerfist.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 19 (3d8 + 6) bludgeoning damage. If the target is a creature, it must succeed on a DC 17 Strength saving throw or be knocked prone.

**Sweeping Axe (Recharge 6).** The warforged titan makes a sweep with its axehand, and each creature within 10 feet of it must make a DC 17 Dexterity saving throw. A creature takes 19 (3d8 + 6) slashing damage on a failed save, or half as much damage on a successful one.


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
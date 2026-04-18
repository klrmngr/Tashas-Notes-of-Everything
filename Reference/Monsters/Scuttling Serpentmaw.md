---
type: pc
race: "Aberration"
class:
 - "Scuttling Serpentmaw"
subClass:
 - "CR 4"
cover: "Scuttling Serpentmaw.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/small
  - cr/4
  - source/crcotn
---
###### Scuttling Serpentmaw
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Scuttling Serpentmaw.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Small Aberration |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 65 (10d6 + 30) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 16 | 3 | 11 | 3 |
| **Mod** | +3 | +2 | +3 | -4 | +0 | -4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 10
**Languages:** —
**Skills:** Stealth +6

---

### Traits

**Amphibious.** The serpentmaw can breathe air and water.

**Pack Tactics.** The serpentmaw has advantage on an attack roll against a creature if at least one of the serpentmaw's allies is within 5 feet of the creature and the ally isn't incapacitated.


---

### Actions

**Multiattack.** The serpentmaw makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +5 to hit, reach 15 ft., one target. *Hit:* 10 (2d6 + 3) piercing damage, or 17 (4d6 + 3) piercing damage if the serpentmaw had advantage on the attack roll.

**Claw.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage.


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
---
type: pc
race: "Aberration"
class:
 - "Light Devourer"
subClass:
 - "CR 6"
cover: "Light Devourer.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/6
  - source/crcotn
---
###### Light Devourer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Light Devourer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 119 (14d8 + 56) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 18 | 18 | 2 | 10 | 3 |
| **Mod** | +4 | +4 | +4 | -4 | +0 | -4 |

**Speed:** 0 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 13
**Languages:** —
**Skills:** Perception +3, Stealth +10
**Damage Immunities:** radiant

---

### Traits

**Light Absorption.** If the light devourer spends any part of its turn in an area of bright light or is subjected to radiant damage, it radiates dim light in a 10-foot radius for 1 hour.

**Water Breathing.** The light devourer can breathe only underwater.


---

### Actions

**Multiattack.** The light devourer makes two Bite attacks.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 21 (5d6 + 4) piercing damage, or radiant damage if the light devourer is radiating light (see Light Absorption).


---

### Bonus Actions

**Radiant Discharge.** If the light devourer is radiating light (see Light Absorption), it releases the light stored in its body in a 20-foot-radius sphere centered on itself, then ceases to radiate light. Each creature in the sphere must make a DC 15 Constitution saving throw, taking 24 (7d6) radiant damage on a failed saving throw, or half as much damage on a successful one.


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
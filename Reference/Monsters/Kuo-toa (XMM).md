---
type: pc
race: "Aberration"
class:
 - "Kuo-toa"
subClass:
 - "CR 1/4"
cover: "Kuo-toa.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/1-4
  - source/xmm
---
###### Kuo-toa
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Kuo-toa.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 18 (4d8) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 10 | 11 | 11 | 10 | 8 |
| **Mod** | +1 | +0 | +0 | +0 | +0 | -1 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., Truesight 30 ft., passive Perception 14
**Languages:** Undercommon
**Skills:** Perception +4

---

### Traits

**Amphibious.** The kuo-toa can breathe air and water.

**Sunlight Sensitivity.** While in sunlight, the kuo-toa has Disadvantage on ability checks and attack rolls.


---

### Actions

**Spear.** m,r +3, reach 5 ft. or range 20/60 ft. *Hit:* 5 (1d8 + 1) Piercing damage.

**Sticky Net (1/Day).** dex DC 10, one Large or smaller creature the kuo-toa can see within 15 feet.  The target has the Restrained condition until the net is destroyed (AC 10; HP 5; Immunity to Bludgeoning, Poison, and Psychic damage). A creature can take an action to make a DC 10 Strength (Athletics) check to free itself or another creature in a net within 5 feet, destroying the net on a success.


---

### Reactions

**Sticky Shield.**  A creature misses the kuo-toa with a melee attack roll using a weapon. dstr DC 11, the triggering creature.  The attack's weapon sticks to the kuo-toa's shield. If the target doesn't let go of the weapon, the target has the Grappled condition while the weapon is stuck (escape DC 11). While stuck, the weapon can't be used. The target can take an action to make a DC 11 Strength (Athletics) check, freeing the weapon on a success.


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
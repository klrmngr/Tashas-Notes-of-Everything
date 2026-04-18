---
type: pc
race: "Humanoid (halfling)"
class:
 - "Boromar Underboss"
subClass:
 - "CR 8"
cover: "Boromar Underboss.png"
campaign:
locations:
tags:
  - race/halfling
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/8
  - source/efa
---
###### Boromar Underboss
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: EFA
___

> [!infobox|no-t right]
> ![[Boromar Underboss.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Small Humanoid (halfling) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 104 (19d6 + 38) |
> | :FasUserGroup: Race | Humanoid (halfling) |
> | :FasBook: Source | EFA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 18 | 15 | 12 | 14 | 17 |
| **Mod** | +0 | +4 | +2 | +1 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 18
**Languages:** Common, Halfling, Thieves' cant
**Saving Throws:** Dex +7, Con +5, Wis +5
**Skills:** Insight +5, Perception +8, Sleight Of Hand +10
**Damage Resistances:** poison

---

### Traits

**Hustle.** The underboss can move through the space of any creature that is of a larger size, but it can't stop there.


---

### Actions

**Multiattack.** The underboss makes three attacks, using Poisoned Blade or Arcane Firearm in any combination.

**Poisoned Blade.** m +7, reach 5 ft. *Hit:* 13 (2d8 + 4) Slashing damage plus 7 (2d6) Poison damage, and the target has the Poisoned condition until the start of the underboss's next turn. If the target is already Poisoned, it instead takes an extra 7 (2d6) Poison damage.

**Arcane Firearm.** r +7, range 30/90 ft. *Hit:* 26 (4d10 + 4) Force damage.


---

### Reactions

**Uncanny Dodge.**  The underboss is hit by an attack roll.  The underboss halves the damage (round down) it takes from that attack.


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
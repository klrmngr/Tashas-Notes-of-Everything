---
type: pc
race: "Undead"
class:
 - "Haint"
subClass:
 - "CR 7"
cover: "Haint.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/7
  - source/jttrc
---
###### Haint
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: JttRC
___

> [!infobox|no-t right]
> ![[Haint.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 75 (10d8 + 30) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | JttRC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 7 | 15 | 17 | 10 | 13 | 17 |
| **Mod** | -2 | +2 | +3 | +0 | +1 | +3 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** any languages it knew in life
**Skills:** Deception +6, Stealth +8
**Damage Resistances:** acid; fire; thunder; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** cold; necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Incorporeal Movement.** The haint can move through other creatures and objects as if they were difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside an object.

**Unusual Nature.** The haint doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The haint makes two Sorrowful Touch attacks.

**Sorrowful Touch.** Melee Spell Attack: +6 to hit, reach 5 ft., one creature. *Hit:* 21 (4d8 + 3) psychic damage.

**Change Shape.** The haint magically assumes the appearance of the Humanoid it was in life, while retaining its game statistics. The assumed appearance ends if the haint is reduced to 0 hit points or uses an action to end it.


---

### Bonus Actions

**Shared Sorrow.** The haint targets one creature it can see within 60 feet of itself that is missing any hit points, sharing its own torment with this pained soul. The target must succeed on a DC 14 Wisdom saving throw or be incapacitated.
A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the haint's Shared Sorrow for the next 24 hours.


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
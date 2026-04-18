---
type: pc
race: "Undead"
class:
 - "Gallows Speaker"
subClass:
 - "CR 6"
cover: "Gallows Speaker.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/6
  - source/vrgr
---
###### Gallows Speaker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Gallows Speaker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 85 (19d8) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 14 | 10 | 10 | 12 | 18 |
| **Mod** | -1 | +2 | +0 | +0 | +1 | +4 |

**Speed:** 0 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** truesight 60 ft., passive Perception 17
**Languages:** any languages its component spirits knew in life
**Saving Throws:** Wis +4
**Skills:** Perception +7
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Divination Senses.** The gallows speaker can see 60 feet into the Ethereal Plane when it is on the Material Plane and vice versa.

**Incorporeal Movement.** The gallows speaker can move through other creatures and objects as if they were 3. It takes 5 (1d10) force damage if it ends it turn inside an object.

**Unusual Nature.** The gallows speaker doesn't require air, food, drink, or sleep.


---

### Actions

**Foretelling Touch.** Melee Spell Attack: +7 to hit, reach 5 ft., one creature. *Hit:* 15 (2d10 + 4) psychic damage, and the target must roll a d4 and subtract the number rolled from the next attack roll or saving throw it makes before the start of the gallows speaker's next turn.

**Suffering Echoes.** The gallows speaker targets a creature it can see within 30 feet of it. The target must make a DC 15 Wisdom saving throw. On a failed save, the target takes 19 (3d12) psychic damage, and waves of painful memories leap from the target to up to three other creatures of the gallows speaker's choice that are within 30 feet of the target, each of which takes 13 (3d8) psychic damage.


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
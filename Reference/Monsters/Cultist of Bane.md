---
type: pc
race: "Humanoid"
class:
 - "Cultist of Bane"
subClass:
 - "CR 9"
cover: "Cultist of Bane.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/9
  - source/fraif
---
###### Cultist of Bane
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Cultist of Bane.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 142 (19d8 + 57) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 16 | 13 | 19 | 15 |
| **Mod** | +4 | +2 | +3 | +1 | +4 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 18
**Languages:** Common
**Saving Throws:** Con +7, Wis +8, Cha +6
**Skills:** Intimidation +6, Perception +8

---

### Traits

**Determined Survivor.** The cultist regains 10 Hit Points at the start of each of its turns if it is Bloodied and has at least 1 Hit Point.


---

### Actions

**Multiattack.** The cultist makes three attacks, using Gauntlet or Oppressive Burst in any combination. It can replace one attack with a use of Spellcasting to cast Dominate Person, if available.

**Gauntlet.** m +8, reach 5 ft. *Hit:* 17 (3d8 + 4) Bludgeoning damage.

**Oppressive Burst.** r +8, range 120 ft. *Hit:* 16 (2d10 + 5) Psychic damage, and the target can't take Reactions until the start of the cultist's next turn.


---

### Reactions

**Counterattack.**  The cultist is hit by an attack roll.  The cultist makes one Gauntlet or Oppressive Burst attack against the triggering creature.


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
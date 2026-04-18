---
type: pc
race: "Humanoid (goblinoid)"
class:
 - "Dum-Dum Goblin"
subClass:
 - "CR 1/4"
cover: "Dum-Dum Goblin.png"
campaign:
locations:
tags:
  - race/goblinoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1-4
  - source/awm
---
###### Dum-Dum Goblin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: AWM
___

> [!infobox|no-t right]
> ![[Dum-Dum Goblin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Humanoid (goblinoid) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 7 |
> | :FasHeart: HP | 7 |
> | :FasUserGroup: Race | Humanoid (goblinoid) |
> | :FasBook: Source | AWM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 14 | 10 | 10 | 8 | 8 |
| **Mod** | -1 | +2 | +0 | +0 | -1 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** —
**Languages:** —

---

### Traits

**Nimble Escape.** The goblin can take the Disengage or Hide action as a bonus action on each of its turns.


---

### Actions

**Catch me if you can!.** Dum-Dum Goblins will opt to run and hide before fighting! A DC 15 Dexterity check must be made before they can be attacked.

**Scimitar.** Melee Weapon Attack: +4 to hit, one target. *Hit:* 3 (1d6 +2) slashing damage.

**Shortbow.** Ranged Weapon Attack: +4 to hit, one target. *Hit:* 6 (1d6 + 2) piercing damage.


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
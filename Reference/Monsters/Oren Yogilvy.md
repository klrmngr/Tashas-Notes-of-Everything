---
type: pc
race: "Humanoid (halfling)"
class:
 - "Oren Yogilvy"
subClass:
 - "CR —"
cover: "Oren Yogilvy.png"
campaign:
locations:
tags:
  - race/halfling
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/—
  - source/skt
---
###### Oren Yogilvy
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Oren Yogilvy.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Small Humanoid (halfling) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 9 (2d6 + 2) |
> | :FasUserGroup: Race | Humanoid (halfling) |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 13 | 12 | 11 | 10 | 16 |
| **Mod** | -1 | +1 | +1 | +0 | +0 | +3 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Halfling
**Skills:** Perception +2, Performance +7, Persuasion +5
**Damage Resistances:** poison

---

### Traits

**Halfling Nimbleness.** Oren can move through the space of any creature that is of a size larger than his.

**Lucky.** When Oren rolls a 1 on an attack roll, ability check, or saving throw, he can reroll the die and must use the new roll.

**Stout Resilience.** Oren has advantage on saving throws against poison

**Roleplaying Information.** Oren came to Nurthfurrow's End looking for easy work and found it. He sings for his supper, drinks like a fish, and wanders the fields at night dreaming up new lyrics to entertain the inn's other guests. Oren likes to stir up trouble from time to time, but he doesn't have a mean bone in his body.
Ideal: "Music is food for the soul."
Bond: "You had me at "Can I buy you a drink."
Flaw: "I have a knack for putting myself in harm's way. Good thing I'm lucky!"


---

### Actions

**Dagger.** Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 3 (1d4 + 1) piercing damage. Duvessa carries only one dagger.


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
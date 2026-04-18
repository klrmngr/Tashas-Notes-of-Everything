---
type: pc
race: "Humanoid (sahuagin)"
class:
 - "Sahuagin Warlock of Uk'otoa"
subClass:
 - "CR 3"
cover: "Sahuagin Warlock of Uk'otoa.png"
campaign:
locations:
tags:
  - race/sahuagin
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/egw
---
###### Sahuagin Warlock of Uk'otoa
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Explorer's Guide to Wildemount
___

> [!infobox|no-t right]
> ![[Sahuagin Warlock of Uk'otoa.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (sahuagin) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 22 (5d8) |
> | :FasUserGroup: Race | Humanoid (sahuagin) |
> | :FasBook: Source | Explorer's Guide to Wildemount |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 10 | 11 | 8 | 8 | 16 |
| **Mod** | +2 | +0 | +0 | -1 | -1 | +3 |

**Speed:** 30 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 9
**Languages:** Common, Sahuagin
**Skills:** Arcana +1, Persuasion +5

---

### Traits

**Blood Frenzy.** The warlock has advantage on melee attack rolls against any creature that doesn't have all its hit points.

**Limited Amphibiousness.** The warlock can breathe air and water, but it needs to be submerged at least once every 4 hours to avoid suffocating.

**Shark Telepathy.** The warlock can magically command any shark within 120 feet of it, using a limited telepathy.


---

### Actions

**Multiattack.** The warlock makes two attacks: one with its bite and one with its Sword of Fathoms.

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. *Hit:* 4 (1d4 + 2) piercing damage.

**Sword of Fathoms.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 7 (1d10 + 2) slashing damage, and if the target is a creature, it must succeed on a DC 13 Constitution saving throw or begin choking. The choking creature is incapacitated until the end of its next turn, when the effect ends on it.

**Eldritch Blast (Cantrip).** Ranged Spell Attack: +5 to hit, range 120 ft., one creature. *Hit:* 5 (1d10) force damage.


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
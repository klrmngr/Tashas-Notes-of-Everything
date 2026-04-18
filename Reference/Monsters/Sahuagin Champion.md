---
type: pc
race: "Humanoid (sahuagin)"
class:
 - "Sahuagin Champion"
subClass:
 - "CR 3"
cover: "Sahuagin Champion.png"
campaign:
locations:
tags:
  - race/sahuagin
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/gos
---
###### Sahuagin Champion
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Sahuagin Champion.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (sahuagin) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 71 (13d8 + 13) |
> | :FasUserGroup: Race | Humanoid (sahuagin) |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 12 | 12 | 13 | 9 |
| **Mod** | +3 | +2 | +1 | +1 | +1 | -1 |

**Speed:** 30 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** Sahuagin
**Skills:** Perception +5

---

### Traits

**Blood Frenzy.** The champion has advantage on melee attack rolls against any creature that doesn't have all its hit points.

**Limited Amphibiousness.** The champion can breathe air and water, but it needs to be submerged at least once every 4 hours to avoid suffocating.

**Shark Telepathy.** The champion can magically command any shark within 120 feet of it, using a limited telepathy.


---

### Actions

**Multiattack.** The champion makes three attacks with its spear, or one attack with its bite and two with its claws.

**Spear.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage, or 7 (1d8 + 3) piercing damage if used with two hands to make a melee attack.

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage.

**Claws.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage.


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
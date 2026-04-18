---
type: pc
race: "Humanoid (sahuagin)"
class:
 - "Sahuagin Coral Smasher"
subClass:
 - "CR 1"
cover: "Sahuagin Coral Smasher.png"
campaign:
locations:
tags:
  - race/sahuagin
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/gos
---
###### Sahuagin Coral Smasher
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Sahuagin Coral Smasher.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (sahuagin) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Humanoid (sahuagin) |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 12 | 12 | 12 | 13 | 9 |
| **Mod** | +3 | +1 | +1 | +1 | +1 | -1 |

**Speed:** 30 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** Sahuagin
**Skills:** Perception +5

---

### Traits

**Blood Frenzy.** The coral smasher has advantage on melee attack rolls against any creature that doesn't have all its hit points.

**Limited Amphibiousness.** The coral smasher can breathe air and water, but it needs to be submerged at least once every 4 hours to avoid suffocating.

**Shark Telepathy.** The coral smasher can magically command any shark within 120 feet of it, using a limited telepathy.

**Siege Monster.** The coral smasher deals double damage to objects and structures.


---

### Actions

**Multiattack.** The coral smasher makes two attacks with its warhammer, or one attack with its bite and one with its claws.

**Warhammer.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) bludgeoning damage.

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage.

**Claws.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) slashing damage.


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
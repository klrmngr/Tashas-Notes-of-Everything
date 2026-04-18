---
type: pc
race: "Humanoid (sahuagin)"
class:
 - "Sahuagin Baron"
subClass:
 - "CR 5"
cover: "Sahuagin Baron.png"
campaign:
locations:
tags:
  - race/sahuagin
  - affinity/hostile
  - type/humanoid
  - size/large
  - cr/5
  - source/mm
---
###### Sahuagin Baron
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Sahuagin Baron.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Humanoid (sahuagin) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 (breastplate) |
> | :FasHeart: HP | 76 (9d10 + 27) |
> | :FasUserGroup: Race | Humanoid (sahuagin) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 15 | 16 | 14 | 13 | 17 |
| **Mod** | +4 | +2 | +3 | +2 | +1 | +3 |

**Speed:** 30 ft., swim 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 17
**Languages:** Sahuagin
**Saving Throws:** Dex +5, Con +6, Int +5, Wis +4
**Skills:** Perception +7

---

### Traits

**Blood Frenzy.** The sahuagin has advantage on melee attack rolls against any creature that doesn't have all its hit points.

**Limited Amphibiousness.** The sahuagin can breathe air and water, but it needs to be submerged at least once every 4 hours to avoid suffocating.

**Shark Telepathy.** The sahuagin can magically command any shark within 120 feet of it, using a limited telepathy.


---

### Actions

**Multiattack.** The sahuagin makes three attacks: one with his bite and two with his claws or trident.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 9 (2d4 + 4) piercing damage.

**Claws.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage.

**Trident.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage, or 13 (2d8 + 4) piercing damage if used with two hands to make a melee attack.


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
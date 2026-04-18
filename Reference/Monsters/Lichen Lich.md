---
type: pc
race: "Undead"
class:
 - "Lichen Lich"
subClass:
 - "CR 18"
cover: "Lichen Lich.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/18
  - source/cm
---
###### Lichen Lich
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Candlekeep Mysteries
___

> [!infobox|no-t right]
> ![[Lichen Lich.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 18 (20,000 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 225 (30d8 + 90) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Candlekeep Mysteries |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 16 | 16 | 14 | 20 | 16 |
| **Mod** | +0 | +3 | +3 | +2 | +5 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 21
**Languages:** Common, Druidic, Sylvan
**Saving Throws:** Con +9, Int +8, Wis +11, Cha +9
**Skills:** Medicine +11, Nature +14, Perception +11, Survival +11
**Damage Resistances:** cold; necrotic
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned; stunned

---

### Traits

**Legendary Resistance (3/Day).** If the lich fails a saving throw, it can choose to succeed instead.

**Rejuvenation.** If it has a phylactery, a destroyed lich gains a new body in 1d10 days, regaining all its hit points and becoming active again. The new body appears within 5 feet of the phylactery.


---

### Actions

**Multiattack.** The lich makes four attacks.

**Poisonous Touch.** Melee Weapon Attack: +9 to hit, reach 10 ft., one creature. *Hit:* 17 (5d6) poison damage, and the target must succeed on a DC 19 Constitution saving throw or be poisoned for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Wither.** Ranged Spell Attack: +9 to hit, range 60 ft., one target. *Hit:* 14 (4d6) necrotic damage.

**Fire Storm (7th-Level Spell; 1/Day).** The lich fills up to ten 10-foot cubes with fire. Every cube must be within 150 feet of the lich and occupy a space the lich can see, and each cube must have at least one face adjacent to the face of another cube. Each creature in the area must make a DC 19 Dexterity saving throw, taking 38 (7d10) fire damage on a failed save, or half as much damage on a successful one. The fire ignites flammable objects in the area that aren't being worn or carried. If the lich chooses, plant life in the area is unaffected by the spell.


---

### Legendary Actions

### 

**Attack.** The lich makes an attack.

**Poison Prick (Cost 2 Actions).** The lich targets one poisoned creature it can see within 30 feet of it. The target must succeed on a DC 19 Constitution saving throw or fall unconscious until the poisoned condition ends on it.

**Sap Life (Costs 2 Actions).** The lich targets one creature it can see within 30 feet of it. The target must succeed on a DC 19 Constitution saving throw or take 11 (2d10) necrotic damage. The lich regains a number of hit points equal to the amount of damage that the creature takes.


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
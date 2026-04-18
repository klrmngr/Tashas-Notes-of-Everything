---
type: pc
race: "Undead"
class:
 - "Lich"
subClass:
 - "CR 21"
cover: "Lich.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/21
  - source/mm
---
###### Lich
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Lich.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 21 (33,000 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral Chaotic Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 135 (18d8 + 54) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 16 | 16 | 20 | 14 | 16 |
| **Mod** | +0 | +3 | +3 | +5 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 19
**Languages:** Common plus up to five other languages
**Saving Throws:** Con +10, Int +12, Wis +9
**Skills:** Arcana +19, History +12, Insight +9, Perception +9
**Damage Resistances:** cold; lightning; necrotic
**Damage Immunities:** poison; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If the lich fails a saving throw, it can choose to succeed instead.

**Rejuvenation.** If it has a phylactery, a destroyed lich gains a new body in 1d10 days, regaining all its hit points and becoming active again. The new body appears within 5 feet of the phylactery.

**Turn Resistance.** The lich has advantage on saving throws against any effect that turns undead.


---

### Actions

**Paralyzing Touch.** Melee Spell Attack: +12 to hit, reach 5 ft., one creature. *Hit:* 10 (3d6) cold damage. The target must succeed on a DC 18 Constitution saving throw or be paralyzed for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


---

### Legendary Actions

### 

**Cantrip.** The lich casts a cantrip.

**Paralyzing Touch (Costs 2 Actions).** The lich uses its Paralyzing Touch.

**Frightening Gaze (Costs 2 Actions).** The lich fixes its gaze on one creature it can see within 10 feet of it. The target must succeed on a DC 18 Wisdom saving throw against this magic or become frightened for 1 minute. The frightened target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a target's saving throw is successful or the effect ends for it, the target is immune to the lich's gaze for the next 24 hours.

**Disrupt Life (Costs 3 Actions).** Each non-undead creature within 20 feet of the lich must make a DC 18 Constitution saving throw against this magic, taking 21 (6d6) necrotic damage on a failed save, or half as much damage on a successful one.


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
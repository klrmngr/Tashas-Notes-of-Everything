---
type: pc
race: "Undead"
class:
 - "Valindra Shadowmantle"
subClass:
 - "CR 21"
cover: "Valindra Shadowmantle.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/21
  - source/toa
---
###### Valindra Shadowmantle
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tomb of Annihilation
___

> [!infobox|no-t right]
> ![[Valindra Shadowmantle.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 21 (33,000 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 135 (18d8 + 54) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Tomb of Annihilation |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 16 | 16 | 20 | 14 | 16 |
| **Mod** | +0 | +3 | +3 | +5 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 19
**Languages:** Common, Abyssal, Draconic, Dwarvish, Elvish, Infernal
**Saving Throws:** Con +10, Int +12, Wis +9
**Skills:** Arcana +19, History +12, Insight +9, Perception +9
**Damage Resistances:** cold; lightning; necrotic
**Damage Immunities:** poison; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Mask.** As a bonus action, Valindra can mask her shriveled flesh and appear to be a living elf. This magical illusion lasts until she ends it as a bonus action or until she uses her Frightening Gaze legendary action. The effect also ends if Valindra drops to 30 hit points or fewer, or if dispel magic is cast on her.

**Preparation.** When preparing her spells, Valindra can swap out any spell on her list of prepared spells for another wizard spell of the same level.

**Legendary Resistance (3/Day).** If Valindra fails a saving throw, she can choose to succeed instead.

**Rejuvenation.** If destroyed Valindra gains a new body in 1d10 days, regaining all her hit points and becoming active again. The new body appears within 5 feet of the phylactery.

**Turn Resistance.** Valindra has advantage on saving throws against any effect that turns undead.


---

### Actions

**Paralyzing Touch.** Melee Spell Attack: +12 to hit, reach 5 ft., one creature. *Hit:* 10 (3d6) cold damage. The target must succeed on a DC 18 Constitution saving throw or be paralyzed for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


---

### Legendary Actions

### 

**Cantrip.** Valindra casts a cantrip.

**Paralyzing Touch (Costs 2 Actions).** Valindra uses her Paralyzing Touch.

**Frightening Gaze (Costs 2 Actions).** Valindra fixes her gaze on one creature she can see within 10 feet of her. The target must succeed on a DC 18 Wisdom saving throw against this magic or become frightened for 1 minute. The frightened target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a target's saving throw is successful or the effect ends for it, the target is immune to the Valindra's gaze for the next 24 hours.

**Disrupt Life (Costs 3 Actions).** Each non-undead creature within 20 feet of Valindra must make a DC 18 Constitution saving throw against this magic, taking 21 (6d6) necrotic damage on a failed save, or half as much damage on a successful one.


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
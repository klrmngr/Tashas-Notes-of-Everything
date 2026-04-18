---
type: pc
race: "Undead"
class:
 - "Acererak"
subClass:
 - "CR 23"
cover: "Acererak.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/23
  - source/toa
---
###### Acererak
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tomb of Annihilation
___

> [!infobox|no-t right]
> ![[Acererak.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 23 (50,000 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 21 (natural armor) |
> | :FasHeart: HP | 285 (30d8 + 150) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Tomb of Annihilation |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 16 | 20 | 27 | 21 | 20 |
| **Mod** | +1 | +3 | +5 | +8 | +5 | +5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 22
**Languages:** Abyssal, Common, Draconic, Dwarvish, Elvish, Giant, Infernal, Primordial, Undercommon
**Saving Throws:** Con +12, Int +15, Wis +12
**Skills:** Arcana +22, History +22, Insight +12, Perception +12
**Damage Resistances:** cold; lightning
**Damage Immunities:** necrotic; poison; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned; stunned

---

### Traits

**Special Equipment.** Acererak carries the Staff of the Forgotten One. He wears a Talisman of the Sphere and has a Sphere of Annihilation under his control.

**Legendary Resistance (3/Day).** If Acererak fails a saving throw, he can choose to succeed instead.

**Rejuvenation.** Acererak's body turns to dust when he drops to 0 hit points, and his equipment is left behind. Acererak gains a new body after 1d10 days, regaining all his hit points and becoming active again. The new body appears within 5 feet of Acererak's phylactery, the location of which is hidden.

**Turn Resistance.** Acererak has advantage on saving throws against any effect that turns undead.


---

### Actions

**Paralyzing Touch.** Melee Spell Attack: +15 to hit, reach 5 ft., one creature. *Hit:* 10 (3d6) cold damage, and the target must succeed on a DC 20 Constitution saving throw or be paralyzed for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Staff (+3 Quarterstaff).** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) bludgeoning damage plus 10 (3d6) necrotic damage, or 8 (1d8 + 4) bludgeoning damage plus 10 (3d6) necrotic damage when used with two hands.

**Invoke Curse.** While holding the Staff of the Forgotten One, Acererak expends 1 charge from it and targets one creature he can see within 60 feet of him. The target must succeed on a DC 23 Constitution saving throw or be cursed. Until the curse is ended, the target can't regain hit points and has vulnerability to necrotic damage. Greater restoration, remove curse, or similar magic ends the curse on the target.


---

### Legendary Actions

### 

**At-Will Spell.** Acererak casts one of his at-will spells.

**Melee Attack.** Acererak uses Paralyzing Touch or makes one melee attack with his staff.

**Frightening Gaze (Costs 2 Actions).** Acererak fixes his gaze on one creature he can see within 10 feet of him. The target must succeed on a DC 20 Wisdom saving throw against this magic or become frightened for 1 minute. The frightened target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a target's saving throw is successful or the effect ends for it, the target its immune to Acererak's gaze for the next 24 hours.

**Talisman of the Sphere (Costs 2 Actions).** Acererak uses his Talisman of the Sphere to move the Sphere of Annihilation under his control up to 90 feet.

**Disrupt Life (Costs 3 Actions).** Each creature within 20 feet of Acererak must make a DC 20 Constitution saving throw against this magic, taking 42 (12d6) necrotic damage on a failed save, or half as much damage on a successful one.


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
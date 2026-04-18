---
type: pc
race: "Undead"
class:
 - "Tarul Var"
subClass:
 - "CR 13"
cover: "Tarul Var.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/13
  - source/tftyp
---
###### Tarul Var
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tales from the Yawning Portal
___

> [!infobox|no-t right]
> ![[Tarul Var.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 105 (14d8 + 42) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Tales from the Yawning Portal |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 16 | 16 | 19 | 14 | 16 |
| **Mod** | +0 | +3 | +3 | +4 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 17
**Languages:** Abyssal, Common, Infernal, Primordial, Thayan
**Saving Throws:** Con +8, Int +9, Wis +7
**Skills:** Arcana +9, History +9, Insight +7, Perception +7
**Damage Resistances:** cold; lightning; necrotic; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Focused Conjuration.** While Var is concentrating on a conjuration spell, his concentration can't be broken as a result of taking damage.

**Legendary Resistance (3/Day).** If Var fails a saving throw, he can choose to succeed instead.

**Rejuvenation.** If Var is destroyed but his phylactery remains intact, Var gains a new body in 1d10 days, regaining all his hit points and becoming active again. The new body appears within 5 feet of the phylactery.

**Turn Resistance.** Var has advantage on saving throws against any effect that turns undead.


---

### Actions

**Paralyzing Touch.** Melee Spell Attack: +9 to hit, reach 5 ft., one creature. *Hit:* 10 (3d6) cold damage. The target must succeed on a DC 17 Constitution saving throw or be paralyzed for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Benign Transposition.** Var teleports up to 30 feet to an unoccupied space he can see. Alternatively, he can choose a space within range that is occupied by a Small or Medium creature. If that creature is willing, both creatures teleport, swapping places. Var can use this feature again only after he finishes a long rest or casts a conjuration spell of 1st level or higher.


---

### Legendary Actions

### 

**Cantrip.** Var casts a cantrip.

**Paralyzing Touch (Costs 2 Actions).** Var uses Paralyzing Touch.

**Frightening Gaze (Costs 2 Actions).** Var fixes his gaze on one creature he can see within 10 feet of him. The target must succeed on a DC 17 Wisdom saving throw against this magic or become frightened for 1 minute. The frightened target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a target's saving throw is successful or the effect ends for it, the target is immune to Var's gaze for the next 24 hours.


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
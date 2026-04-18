---
type: pc
race: "Undead"
class:
 - "Undying Councilor"
subClass:
 - "CR 10"
cover: "Undying Councilor.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/10
  - source/erlw
---
###### Undying Councilor
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Undying Councilor.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 104 (16d8 + 32) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 10 | 14 | 17 | 21 | 16 |
| **Mod** | +3 | +0 | +2 | +3 | +5 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 19
**Languages:** Common, Elvish
**Saving Throws:** Con +6, Int +7, Wis +9
**Skills:** Arcana +7, History +11, Insight +9, Perception +9, Religion +7
**Damage Vulnerabilities:** necrotic
**Damage Immunities:** poison; radiant
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Aura of Radiance.** The councilor magically sheds bright light in a 15-foot radius and dim light for an additional 15 feet. The councilor can extinguish or restore this light as a bonus action. If the bright light overlaps with an area of darkness created by a spell of 3rd level or lower, the spell that created that darkness is dispelled.

**Magic Resistance.** The councilor has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The councilor makes two Radiant Touch attacks.

**Radiant Touch.** Melee Spell Attack: +9 to hit, reach 5 ft., one target. *Hit:* 15 (3d6 + 5) radiant damage.

**Healing Touch (3/Day).** The councilor touches another creature. The target magically regains 18 (3d8 + 5) hit points and is freed from one curse afflicting it (councilor's choice).

**Flame Strike (5th-Level Spell; Requires a Spell Slot).** The councilor chooses a point it can see within 60 feet of it. Each creature in a 10-foot-radius, 40-foot-high cylinder centered on that point must make a DC 17 Dexterity saving throw. A creature takes 14 (4d6) fire damage and 14 (4d6) radiant damage on a failed save, or half as much damage on a successful one. If the councilor casts this spell using a spell slot of 6th level or higher, the fire damage or the radiant damage (its choice) increases by 1d6 for each slot level above 5th.


---

### Legendary Actions

### 

**Touch.** The councilor makes one attack with its Radiant Touch.

**Shimmering Aura (Costs 2 Actions).** The councilor channels positive energy into its Aura of Radiance. Until the end of the councilor's next turn, it sheds bright light in a 30-foot radius and dim light for an additional 30 feet. Any creature that starts its turn in the bright light must succeed on a DC 17 Constitution saving throw or be blinded until the end of the councilor's next turn.


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
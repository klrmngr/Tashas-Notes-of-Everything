---
type: pc
race: "Undead"
class:
 - "False Lich"
subClass:
 - "CR 21"
cover: "False Lich.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/21
  - source/veor
---
###### False Lich
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[False Lich.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 21 (33,000 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 199 (21d8 + 105) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 20 | 25 | 19 | 15 |
| **Mod** | +0 | +3 | +5 | +7 | +4 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 60 ft., passive Perception 14
**Languages:** Abyssal, Common, Draconic, Dwarvish, Elvish, Giant, Infernal, Primordial, Undercommon
**Saving Throws:** Con +12, Int +14, Wis +11, Cha +9
**Damage Immunities:** necrotic; poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned; stunned

---

### Traits

**Legendary Resistance (3/Day).** If the false lich fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The false lich has advantage on saving throws against spells and magical effects.


---

### Actions

**Multiattack.** The false lich makes two Death Rend attacks and uses Bloodcurdling Lament if available.

**Death Rend.** Melee Spell Attack: +14 to hit, reach 5 ft., one target. *Hit:* 23 (3d10 + 7) necrotic damage.

**Bloodcurdling Lament (Recharge 5–6).** The false lich emits a hideous shriek charged with malignant energy. Each creature within 30 feet of the false lich must succeed on a DC 22 Wisdom saving throw or have the frightened condition for 1 minute. While frightened in this way, a creature also has the unconscious condition. An affected creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


---

### Bonus Actions

**Soul Siphon.** The false lich targets one creature it can see within 120 feet of itself. The target must make a DC 22 Charisma saving throw; if the target has the unconscious condition, it has disadvantage on this saving throw. The target takes 21 (6d6) force damage on a failed save or half as much damage on a successful one. The false lich then regains a number of hit points equal to the amount of force damage taken.
If this damage reduces the target to 0 hit points, the target immediately dies, its body disappears, and its soul is trapped inside one of the soul gems within the false lich's skull. After 24 hours, the gem transfers the soul to the false lich's creator.
When the false lich is reduced to 0 hit points, it is destroyed and disintegrates, leaving behind the gems. Crushing a gem releases any souls trapped within, at which point the soul's body re-forms in an unoccupied space nearest to the gem and in the same state as it was when its soul was trapped.


---

### Legendary Actions

### 

**Spiteful Teleport.** The false lich, along with anything it is wearing or carrying, teleports to an unoccupied space it can see within 60 feet of itself. It then makes one Death Rend attack if possible.

**Cast a Spell (Costs 2 Actions).** The false lich uses Spellcasting.


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
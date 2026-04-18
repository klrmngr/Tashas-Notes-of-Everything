---
type: pc
race: "Undead"
class:
 - "Demilich"
subClass:
 - "CR 18"
cover: "Demilich.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/tiny
  - cr/18
  - source/mm
---
###### Demilich
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Demilich.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 18 (20,000 XP) |
> | :RiSwordFill: Type | Tiny Undead |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 80 (32d4) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 20 | 10 | 20 | 17 | 20 |
| **Mod** | -5 | +5 | +0 | +5 | +3 | +5 |

**Speed:** 0 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 13
**Languages:** —
**Saving Throws:** Con +6, Int +11, Wis +9, Cha +11
**Damage Resistances:** bludgeoning, piercing, slashing from magic weapons
**Damage Immunities:** necrotic; poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned; prone; stunned

---

### Traits

**Avoidance.** If the demilich is subjected to an effect that allows it to make a saving throw to take only half damage, it instead takes no damage if it succeeds on the saving throw, and only half damage if it fails.

**Legendary Resistance (3/Day).** If the demilich fails a saving throw, it can choose to succeed instead.

**Turn Immunity.** The demilich is immune to effects that turn undead.


---

### Actions

**Howl (Recharge 5–6).** The demilich emits a bloodcurdling howl. Each creature within 30 feet of the demilich that can hear the howl must succeed on a DC 15 Constitution saving throw or drop to 0 hit points. On a successful save, the creature is frightened until the end of its next turn.

**Life Drain.** The demilich targets up to three creatures that it can see within 10 feet of it. Each target must succeed on a DC 19 Constitution saving throw or take 21 (6d6) necrotic damage, and the demilich regains hit points equal to the total damage dealt to all targets.


---

### Legendary Actions

### 

**Flight.** The demilich flies up to half its flying speed.

**Cloud of Dust.** The demilich magically swirls its dusty remains. Each creature within 10 feet of the demilich, including around a corner, must succeed on a DC 15 Constitution saving throw or be blinded until the end of the demilich's next turn. A creature that succeeds on the saving throw is immune to this effect until the end of the demilich's next turn.

**Energy Drain (Costs 2 Actions).** Each creature with in 30 feet of the demilich must make a DC 15 Constitution saving throw. On a failed save, the creature's hit point maximum is magically reduced by 10 (3d6). If a creature's hit point maximum is reduced to 0 by this effect, the creature dies. A creature's hit point maximum can be restored with the  greater restoration spell or similar magic.

**Vile Curse (Costs 3 Actions).** The demilich targets one creature it can see within 30 feet of it. The target must succeed on a DC 15 Wisdom saving throw or be magically cursed. Until the curse ends, the target has disadvantage on attack rolls and saving throws. The target can repeat the saving throw at the end of each of its turns, ending the curse on a success.


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
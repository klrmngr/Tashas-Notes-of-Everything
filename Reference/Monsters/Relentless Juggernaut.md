---
type: pc
race: "Fiend"
class:
 - "Relentless Juggernaut"
subClass:
 - "CR 12"
cover: "Relentless Juggernaut.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/12
  - source/vrgr
---
###### Relentless Juggernaut
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Relentless Juggernaut.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Large Fiend |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 161 (14d10 + 84) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 12 | 22 | 8 | 15 | 16 |
| **Mod** | +6 | +1 | +6 | -1 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** understands all languages but can't speak
**Saving Throws:** Dex +5, Wis +6, Cha +7
**Skills:** Perception +6, Survival +6
**Condition Immunities:** charmed; exhaustion; frightened

---

### Traits

**Legendary Resistance (3/Day).** If the juggernaut fails a saving throw, it can choose to succeed instead.

**Regeneration.** The juggernaut regains 20 hit points at the start of its turn. If the juggernaut takes radiant damage, this trait doesn't function at the start of its next turn. The juggernaut dies only if it starts its turn with 0 hit points and doesn't regenerate.

**Unusual Nature.** The juggernaut doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The juggernaut makes two attacks. It can replace one attack with Deadly Shaping if it is ready.

**Executioner's Pick.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 17 (2d10 + 6) piercing damage, and if the target is a creature, its speed is reduced by 10 feet until the start of the juggernaut's next turn.

**Fist.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 11 (1d10 + 6) bludgeoning damage, and if the target is a Large or smaller creature, it must succeed on a DC 18 Strength saving throw or be knocked prone.

**Deadly Shaping (Recharge 5–6).** The juggernaut magically shapes a feature of its surroundings into a deadly implement. A creature the juggernaut can see within 60 feet of it must make a DC 18 Dexterity saving throw. If the saving throw fails, the targeted creature is struck by one of the following (juggernaut's choice):

**Flying Stone.** The target takes 22 (5d8) bludgeoning damage and is incapacitated until the start of the juggernaut's next turn, and the implement vanishes.

**Scything Shrapnel.** The target takes 14 (4d6) slashing damage, and the implement vanishes. At the start of each of its turns, the target takes 10 (3d6) necrotic damage from the wound left by the shrapnel. The wound ends if the target regains any hit points or if a creature uses an action to stanch the wound, which requires a successful DC 15 Wisdom (Medicine) check.


---

### Legendary Actions

### 

**Implacable Advance.** The juggernaut moves up to its speed, ignoring 3. Any object in its path takes 55 (10d10) bludgeoning damage if it isn't being worn or carried.

**Rapid Shaping (Costs 3 Actions).** The juggernaut recharges Deadly Shaping and uses it.


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
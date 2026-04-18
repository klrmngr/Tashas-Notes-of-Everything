---
type: pc
race: "Humanoid (human, wizard)"
class:
 - "Oracle of Strixhaven"
subClass:
 - "CR 15"
cover: "Oracle of Strixhaven.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/15
  - source/scc
---
###### Oracle of Strixhaven
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Oracle of Strixhaven.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human, wizard) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 150 (20d8 + 60) |
> | :FasUserGroup: Race | Humanoid (human, wizard) |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 15 | 16 | 21 | 20 | 18 |
| **Mod** | +1 | +2 | +3 | +5 | +5 | +4 |

**Speed:** 30 ft., fly 15 ft. ((hover)) &nbsp;|&nbsp; **Senses:** passive Perception 20
**Languages:** all
**Saving Throws:** Con +8, Int +10, Wis +10, Cha +9
**Skills:** Arcana +15, Insight +15, Investigation +15, Nature +10, Perception +10
**Condition Immunities:** charmed; frightened

---

### Traits

**Legendary Resistance (3/Day).** If the Oracle fails a saving throw, she can choose to succeed instead.


---

### Actions

**Multiattack.** The Oracle makes two Magic Flare attacks. She can also use Paradoxy, if available.

**Magic Flare.** Melee or Ranged Spell Attack: +10 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 24 (3d12 + 5) force damage.

**Paradoxy (Recharge 4–6).** Momentary warps in reality appear at three different points the Oracle can see within 120 feet of her. Each creature in a 20-foot-radius sphere centered on each point must make a DC 18 Strength saving throw. On a failed save, a creature takes 33 (6d10) force damage and is pulled up to 15 feet in a straight line toward the center of the sphere. On a successful save, the creature takes half as much damage and isn't pulled. A creature caught in the area of multiple warps is affected by only one, which the Oracle chooses.

**Teleport.** The Oracle teleports, along with any equipment she is wearing or carrying, to an unoccupied space she can see within 60 feet of herself.


---

### Legendary Actions

### 

**Vector Shift.** The Oracle teleports one creature she can see within 60 feet of herself, along with any equipment it is wearing or carrying, to an unoccupied space within 30 feet of herself. An unwilling target must succeed on a DC 18 Charisma saving throw to avoid the effect.

**Spellcasting (Costs 2 Actions).** The Oracle uses Spellcasting.

**Vortex Jaunt (Costs 2 Actions).** The Oracle uses Teleport, and immediately after she disappears, each creature within 30 feet of the space she left must succeed on a DC 18 Constitution saving throw or take 16 (3d10) force damage.


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
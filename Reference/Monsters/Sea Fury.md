---
type: pc
race: "Fey"
class:
 - "Sea Fury"
subClass:
 - "CR 12"
cover: "Sea Fury.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/12
  - source/egw
---
###### Sea Fury
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Explorer's Guide to Wildemount
___

> [!infobox|no-t right]
> ![[Sea Fury.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 105 (14d8 + 42) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | Explorer's Guide to Wildemount |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 15 | 16 | 12 | 12 | 18 |
| **Mod** | +4 | +2 | +3 | +1 | +1 | +4 |

**Speed:** 30 ft., swim 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** Aquan, Common, Giant
**Skills:** Deception +8, Insight +5, Perception +5, Stealth +6
**Damage Immunities:** cold; fire; poison; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Condition Immunities:** paralyzed; poisoned

---

### Traits

**Amphibious.** The sea fury can breathe air and water.

**Legendary Resistance (3/Day).** If the sea fury fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The sea fury has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The sea fury makes two attacks with its claws.

**Claws.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) slashing damage.

**Death Glare.** The sea fury targets one frightened creature it can see within 30 feet of it. The target must succeed on a DC 16 Wisdom saving throw or drop to 0 hit points.


---

### Legendary Actions

### 

**As Water.** The sea fury transforms into a wave of foaming seawater, along with whatever it is wearing or carrying, and moves up to its speed without provoking opportunity attacks. While in this form, it can't be grappled or restrained. It reverts to its true form at the end of this movement.

**Fearsome Apparition (Costs 2 Actions).** The sea fury conjures an apparition of one of its dead sisters, which appears in an unoccupied space the sea fury can see within 30 feet of it. Enemies of the sea fury that can see the apparition must succeed on a DC 16 Wisdom saving throw or be frightened of it until it vanishes at the end of the sea fury's next turn.

**Conjure Snakes (Costs 3 Actions).** The sea fury disgorges a swarm of poisonous snakes, which occupies the same space as the sea fury, acts on its own initiative count, and attacks as directed by the sea fury. The sea fury can control up to three of these swarms at a time.


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
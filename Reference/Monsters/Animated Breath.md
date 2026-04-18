---
type: pc
race: "Elemental"
class:
 - "Animated Breath"
subClass:
 - "CR 6"
cover: "Animated Breath.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/6
  - source/ftd
---
###### Animated Breath
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Animated Breath.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Elemental |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor); 17 cold form only |
> | :FasHeart: HP | 95 (10d10 + 40) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 11 | 18 | 6 | 10 | 5 |
| **Mod** | +4 | +0 | +4 | -2 | +0 | -3 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** understands Draconic but can't speak
**Condition Immunities:** exhaustion; paralyzed; petrified; poisoned; restrained; unconscious

---

### Traits

**Chromatic Form.** When created, the animated breath takes one of five forms, matching its creator's breath weapon: Acid, Cold, Fire, Lightning, or Poison. This form determines the creature's AC, damage resistance, traits, and attacks.

**Fire Aura (Fire Form Only).** At the start of each of the animated breath's turns, each creature within 5 feet of it takes 3 (1d6) fire damage, and flammable objects in the aura that aren't being worn or carried ignite. A creature that touches the animated breath or hits it with a melee attack takes 3 (1d6) fire damage.

**Putrid Aura (Acid and Poison Forms Only).** A creature that starts its turn within 5 feet of the animated breath must succeed on a DC 15 Constitution saving throw or be poisoned until the start of its next turn. A creature that touches the animated breath or hits it with a melee attack takes 3 (1d6) acid damage.


---

### Actions

**Multiattack.** The animated breath makes two Slam attacks.

**Slam.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) bludgeoning damage plus 11 (2d10) damage of a type determined by the animated breath's form: acid, cold, fire, lightning, or poison.


---

### Bonus Actions

**Lightning Burst (Lightning Form Only).** The animated breath magically teleports to an unoccupied space it can see within 30 feet of it. Each creature within 5 feet of the animated breath after it teleports takes 3 (1d6) lightning damage.


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
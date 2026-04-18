---
type: pc
race: "Undead"
class:
 - "Harrow Hound"
subClass:
 - "CR 3"
cover: "Harrow Hound.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/3
  - source/bmt
---
###### Harrow Hound
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Harrow Hound.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 45 (6d8 + 18) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 19 | 16 | 8 | 15 | 13 |
| **Mod** | +3 | +4 | +3 | -1 | +2 | +1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 16
**Languages:** Blink Dog, understands Sylvan but can't speak it
**Skills:** Perception +6, Stealth +6
**Damage Resistances:** necrotic; psychic; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Pack Tactics.** The hound has advantage on attack rolls against a creature if at least one of the hound's allies is within 5 feet of the target and the ally doesn't have the incapacitated condition.

**Supernatural Tracker.** The hound knows the distance to and direction of any creature that has come within 30 feet of it, even if that creature is on a different plane of existence. If the creature being tracked by the hound dies, the hound knows.


---

### Actions

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) piercing damage plus 3 (1d6) necrotic damage. If the target is a creature, it must succeed on a DC 13 Strength saving throw or have the prone condition.


---

### Bonus Actions

**Shadow Step (Recharge 4–6).** The hound magically teleports, along with any equipment it is wearing or carrying, up to 40 feet to an unoccupied space it can see.


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
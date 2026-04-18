---
type: pc
race: "Undead"
class:
 - "Frost Giant Zombie"
subClass:
 - "CR 9"
cover: "Frost Giant Zombie.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/huge
  - cr/9
  - source/egw
---
###### Frost Giant Zombie
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Explorer's Guide to Wildemount
___

> [!infobox|no-t right]
> ![[Frost Giant Zombie.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Huge Undead |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (patchwork armor) |
> | :FasHeart: HP | 138 (12d12 + 60) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Explorer's Guide to Wildemount |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 6 | 21 | 3 | 6 | 5 |
| **Mod** | +6 | -2 | +5 | -4 | -2 | -3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 8
**Languages:** understands Giant but can't speak
**Saving Throws:** Wis +2
**Damage Immunities:** cold; poison
**Condition Immunities:** poisoned

---

### Traits

**Numbing Aura.** Any creature that starts its turn within 10 feet of the zombie must make a DC 17 Constitution saving throw. Unless the save succeeds, the creature can't make more than one attack, or take a bonus action on that turn.

**Undead Fortitude.** If damage reduces the zombie to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is fire, radiant, or from a critical hit. On a success, the zombie drops to 1 hit point instead.


---

### Actions

**Multiattack.** The zombie makes two weapon attacks.

**Greataxe.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 25 (3d12 + 6) slashing damage.

**Hurl Rock.** Ranged Weapon Attack: +10 to hit, range 60/240 ft., one target. *Hit:* 28 (4d10 + 6) bludgeoning damage.

**Freezing Stare.** The zombie targets one creature it can see within 60 feet of it. The target must succeed on a DC 17 Constitution saving throw or take 35 (10d6) cold damage and be paralyzed until the end of its next turn.


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
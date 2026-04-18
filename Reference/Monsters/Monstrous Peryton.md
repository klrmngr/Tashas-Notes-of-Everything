---
type: pc
race: "Monstrosity"
class:
 - "Monstrous Peryton"
subClass:
 - "CR 11"
cover: "Monstrous Peryton.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/11
  - source/gos
---
###### Monstrous Peryton
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Monstrous Peryton.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 144 (17d10 + 51) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 14 | 16 | 9 | 14 | 10 |
| **Mod** | +4 | +2 | +3 | -1 | +2 | +0 |

**Speed:** 20 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 16
**Languages:** understands Common and Elvish but can't speak
**Saving Throws:** Str +8, Dex +6, Wis +6
**Skills:** Perception +6

---

### Traits

**Flyby.** The peryton doesn't provoke opportunity attacks when it flies out of an enemy's reach.

**Keen Sight and Smell.** The peryton has advantage on Wisdom (Perception) checks that rely on sight or smell.

**Legendary Resistance (3/Day).** If the peryton fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The peryton makes two attacks: one with its gore and one with its talons.

**Gore.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) piercing damage.

**Talons.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 16 (2d10 + 5) slashing damage.

**Warp Shadow.** The peryton chooses up to three creatures within 60 feet of it that it can see. Each creature must succeed on a DC 14 Wisdom saving throw or become cursed. While cursed, whenever the creature makes an attack roll, an ability check, or a saving throw, it must roll a d4 and subtract that number from the roll. A cursed creature can repeat this saving throw at the end of each of its turns, ending the effect on itself with a success. A creature that succeeds on this saving throw is immune to this peryton's Warp Shadow for 24 hours.


---

### Legendary Actions

### 

**Detect.** The peryton makes a Wisdom (Perception) check.

**Talons Attack.** The peryton makes one attack with its talons.

**Dive Attack (Costs 2 Actions).** The peryton moves up to its speed toward one target of its choosing. It then makes a gore attack that deals an extra 9 (2d8) piercing damage on a hit.


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
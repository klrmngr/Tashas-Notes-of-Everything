---
type: pc
race: "Humanoid (any race)"
class:
 - "Tarkanan Assassin"
subClass:
 - "CR 2"
cover: "Tarkanan Assassin.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/erlw
---
###### Tarkanan Assassin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Tarkanan Assassin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral Chaotic Evil |
> | :FasShield: AC | 15 (studded leather) |
> | :FasHeart: HP | 45 (7d8 + 14) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 16 | 14 | 10 | 14 | 11 |
| **Mod** | +1 | +3 | +2 | +0 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Common, Thieves' cant
**Skills:** Athletics +3, Deception +2, Perception +4, Sleight Of Hand +5, Stealth +5

---

### Traits

**Unstable Mark.** When the assassin casts an innate spell, each creature within 10 feet of the assassin must make a DC 12 Constitution saving throw, taking 4 (1d8) force damage on a failed save, or half as much damage on a successful one.


---

### Actions

**Multiattack.** The assassin makes two shortsword attacks.

**Shortsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage plus 7 (2d6) poison damage.

**Fire Bolt (Cantrip).** Ranged Spell Attack: +4 to hit, range 120 ft., one target. *Hit:* 11 (2d10) fire damage. A flammable object hit by this spell ignites if it isn't being worn or carried.

**Chromatic Orb (1/Day).** Ranged Spell Attack: +4 to hit, range 90 ft., one creature. *Hit:* 18 (4d8) damage of a type chosen by the assassin: acid, cold, fire, lightning, poison, or thunder.


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
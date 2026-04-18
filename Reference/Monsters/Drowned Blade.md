---
type: pc
race: "Undead"
class:
 - "Drowned Blade"
subClass:
 - "CR 2"
cover: "Drowned Blade.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/2
  - source/gos
---
###### Drowned Blade
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Drowned Blade.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 10 (leather armor) |
> | :FasHeart: HP | 45 (6d8 + 18) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 8 | 16 | 3 | 9 | 5 |
| **Mod** | +3 | -1 | +3 | -4 | -1 | -3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 9
**Languages:** understands the languages it knew in life but can't speak
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Bottom Treader.** The drowned blade cannot swim, and it sinks to the bottom of any body of water. It takes no penalties to its movement or attacks underwater. It is immune to the effects of being underwater at a depth greater than 100 feet.

**Bound Together.** The drowned blade shares its mind with every other drowned one within 1 mile of it, and can communicate its thoughts and observations to them instantaneously and without limitation.

**Undead Fortitude.** If damage reduces the drowned blade to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the drowned blade drops to 1 hit point instead.


---

### Actions

**Multiattack.** The drowned blade makes two rusted longsword attacks.

**Rusted Longsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage, and the target must succeed on a DC 12 Constitution saving throw or contract bluerot (see the "Bluerot" in notes).


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
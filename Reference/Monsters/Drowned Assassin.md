---
type: pc
race: "Undead"
class:
 - "Drowned Assassin"
subClass:
 - "CR 4"
cover: "Drowned Assassin.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/4
  - source/gos
---
###### Drowned Assassin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Drowned Assassin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 (leather armor) |
> | :FasHeart: HP | 67 (9d8 + 27) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 16 | 16 | 9 | 9 | 16 |
| **Mod** | +2 | +3 | +3 | -1 | -1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 9
**Languages:** understands the languages it knew in life but can't speak
**Saving Throws:** Dex +5, Con +5
**Skills:** Intimidation +5, Stealth +5
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Bottom Treader.** The drowned assassin cannot swim, and it sinks to the bottom of any body of water. It takes no penalties to its movement or attacks underwater. It is immune to the effects of being underwater at a depth greater than 100 feet.

**Bound Together.** The drowned assassin shares its mind with every other drowned one within 1 mile of it, and can communicate its thoughts and observations to them instantaneously and without limitation.

**Undead Fortitude.** If damage reduces the drowned assassin to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the drowned assassin drops to 1 hit point instead.


---

### Actions

**Multiattack.** The drowned assassin makes two hand crossbow attacks or two dagger attacks. It can then take the Dash, Disengage, or Hide action.

**Hand Crossbow.** Ranged Weapon Attack: +5 to hit, range 30/120 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage plus 3 (1d6) poison damage, and the target must succeed on a DC 12 Constitution saving throw or contract bluerot (see the "Bluerot" in notes).

**Dagger.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage plus 9 (2d8) poison damage, and the target must succeed on a DC 12 Constitution saving throw or contract bluerot (see the "Bluerot" in notes).

**Reveal (1/Day).** The drowned assassin removes its mask, revealing its rotting face. Each creature of the assassin's choice within 30 feet of it that can see the assassin must succeed on a DC 13 Wisdom saving throw or be frightened until the end of its next turn.


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
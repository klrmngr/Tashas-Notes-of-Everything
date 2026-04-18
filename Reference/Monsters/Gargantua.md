---
type: pc
race: "Aberration"
class:
 - "Gargantua"
subClass:
 - "CR 21"
cover: "Gargantua.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/gargantuan
  - cr/21
  - source/bgg
---
###### Gargantua
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Gargantua.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 21 (33,000 XP) |
> | :RiSwordFill: Type | Gargantuan Aberration |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 388 (21d20 + 168) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 10 | 26 | 9 | 16 | 18 |
| **Mod** | +8 | +0 | +8 | -1 | +3 | +4 |

**Speed:** 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 13
**Languages:** Giant
**Saving Throws:** Dex +7, Int +6, Wis +10
**Damage Resistances:** force; psychic
**Condition Immunities:** frightened

---

### Traits

**Weird Aura.** At the start of each of the gargantua's turns, each creature of the gargantua's choice within 30 feet of it must make a DC 19 Wisdom saving throw. On a failed save, a target sees the gargantua as a manifestation of the target's worst fears; it takes 17 (5d6) psychic damage and has the frightened condition until the start of the target's next turn. On a successful save, a target is immune to this gargantua's Weird Aura for 24 hours.


---

### Actions

**Multiattack.** The gargantua makes two Slam or Rock attacks.

**Slam.** Melee Weapon Attack: +15 to hit, reach 20 ft., one target. *Hit:* 27 (3d12 + 8) bludgeoning damage.

**Rock.** Ranged Weapon Attack: +15 to hit, range 120/480 ft., one target. *Hit:* 24 (3d10 + 8) bludgeoning damage.


---

### Bonus Actions

**Baleful Hex.** The gargantua curses one creature it can see within 120 feet of itself. The target must succeed on a DC 19 Wisdom saving throw or have the incapacitated condition until the end of its next turn.

**Teleport.** The gargantua teleports, along with any equipment it is wearing or carrying, to an unoccupied space that it can see within 120 feet of itself.


---

### Reactions

**Flick.** Immediately after the gargantua takes damage from a Large or smaller creature it can see within 20 feet of itself, it attempts to flick the creature away. The target must succeed on a DC 23 Strength saving throw, or the target takes 18 (3d6 + 8) bludgeoning damage, is pushed horizontally up to 100 feet away from the gargantua, and has the prone condition.

**Spell Mimicry (1/Day).** Immediately after a creature the gargantua can see casts a spell of 5th level or lower, the gargantua tries to copy the spell. That creature must succeed on a DC 19 Charisma saving throw, or the gargantua immediately casts the same spell at the same level (+11 to hit with spell attacks, spell save DC 19), requiring no material components and choosing the spell's targets.


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
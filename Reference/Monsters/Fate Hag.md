---
type: pc
race: "Fey"
class:
 - "Fate Hag"
subClass:
 - "CR 4"
cover: "Fate Hag.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/4
  - source/bmt
---
###### Fate Hag
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Fate Hag.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 71 (13d8 + 13) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 14 | 13 | 12 | 18 | 15 |
| **Mod** | +1 | +2 | +1 | +1 | +4 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 60 ft., passive Perception 16
**Languages:** all
**Saving Throws:** Con +3, Wis +6
**Skills:** Arcana +5, Deception +6, History +5, Perception +6
**Condition Immunities:** charmed

---

### Traits

**Legendary Resistance (2/Day).** If the hag fails a saving throw, it can choose to succeed instead.

**Trace the Threads (1/Day).** The hag can cast the Legend Lore spell, requiring no material components and using Wisdom as the spellcasting ability.


---

### Actions

**Multiattack.** The hag makes two Shears attacks. It can replace one attack with a use of Spellcasting.

**Shears.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) force damage. If the target is a creature, it has disadvantage on attack rolls until the end of the hag's next turn.


---

### Legendary Actions

### 

**Destined Jaunt.** The hag magically teleports, along with any equipment it is wearing or carrying, to an unoccupied space it can see within 30 feet of itself.

**Tangle Threads.** The hag magically tangles a creature it can see within 60 feet of itself in spectral silver threads. The creature must succeed on a DC 14 Strength saving throw, or its speed is reduced to 0 until the end of its next turn.

**Destiny Curse (Costs 2 Actions).** The hag magically curses a creature it can see within 60 feet of itself. The creature must make a DC 14 Wisdom saving throw, and the creature has disadvantage on this save if it has damaged the hag within the last minute. On a failed save, the creature has disadvantage on ability checks, attack rolls, and saving throws until the curse ends. Once per turn, when the cursed creature fails one of those d20 rolls, it takes 7 (2d6) force damage. The curse ends after 1 minute; when the creature succeeds on a total of three ability checks, attack rolls, or saving throws in any combination; or when the hag uses this action again.


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
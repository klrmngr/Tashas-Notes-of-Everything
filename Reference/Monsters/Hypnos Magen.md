---
type: pc
race: "Construct"
class:
 - "Hypnos Magen"
subClass:
 - "CR 1"
cover: "Hypnos Magen.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/1
  - source/idrotf
---
###### Hypnos Magen
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Hypnos Magen.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 34 (4d8 + 16) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 18 | 14 | 10 | 7 |
| **Mod** | +0 | +2 | +4 | +2 | +0 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** understands the languages of its creator but can't speak, telepathy 30 ft.
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Fiery End.** If the magen dies, its body disintegrates in a harmless burst of fire and smoke, leaving behind anything it was wearing or carrying.

**Magic Resistance.** The magen has advantage on saving throws against spells and other magical effects.

**Unusual Nature.** The magen doesn't require air, food, drink, or sleep.


---

### Actions

**Psychic Lash.** The magen's eyes glow silver as it targets one creature that it can see within 60 feet of it. The target must succeed on a DC 12 Wisdom saving throw or take 11 (2d10) psychic damage.

**Suggestion.** The magen casts the suggestion spell (save DC 12), requiring no material components. The target must be a creature that the magen can communicate with telepathically. If it succeeds on its saving throw, the target is immune to this magen's suggestion spell for the next 24 hours. The magen's spellcasting ability is Intelligence.


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
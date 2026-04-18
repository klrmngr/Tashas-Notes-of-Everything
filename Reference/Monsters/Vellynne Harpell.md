---
type: pc
race: "Humanoid (human)"
class:
 - "Vellynne Harpell"
subClass:
 - "CR 4"
cover: "Vellynne Harpell.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/4
  - source/idrotf
---
###### Vellynne Harpell
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Vellynne Harpell.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 13 (bracers of defense) |
> | :FasHeart: HP | 67 (9d8 + 27) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 12 | 17 | 18 | 15 | 13 |
| **Mod** | +0 | +1 | +3 | +4 | +2 | +1 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Draconic, Dwarvish, Elvish, Orc
**Saving Throws:** Int +6, Wis +4
**Skills:** Arcana +6, History +6

---

### Traits

**Special Equipment.** Vellynne wears bracers of defense and carries a wand of magic missiles (see "Actions" below).


---

### Actions

**Vampiric Touch (3rd-Level Spell; Requires a Spell Slot).** Melee Spell Attack: +6 to hit, reach 5 ft., one creature. *Hit:* 10 (3d6) necrotic damage, and Vellynne regains hit points equal to half the necrotic damage dealt. If Vellynne casts this spell using a spell slot of 4th level or higher, the necrotic damage increases by 1d6 for each slot level above 3rd.

**Chill Touch (Cantrip).** Ranged Spell Attack: +6 to hit, range 120 ft., one creature. *Hit:* 9 (2d8) necrotic damage, and the target can't regain hit points until the start of Vellynne's next turn.

**Wand of Magic Missiles.** While holding this wand, Vellynne can expend 1 or more of its 7 charges to cast the magic missile spell from it. She can expend 1 charge to cast the 1st-level version of the spell. She can increase the spell slot level by one for each additional charge she expends. The wand regains 1d6 + 1 expended charges daily at dawn. If the wand's last charge is expended, roll a d20; on a 1, the wand crumbles into ashes and is destroyed.


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
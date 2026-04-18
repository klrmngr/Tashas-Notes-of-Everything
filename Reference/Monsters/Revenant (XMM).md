---
type: pc
race: "Undead"
class:
 - "Revenant"
subClass:
 - "CR 5"
cover: "Revenant.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/5
  - source/xmm
---
###### Revenant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Revenant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 127 (15d8 + 60) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 18 | 13 | 16 | 18 |
| **Mod** | +4 | +2 | +4 | +1 | +3 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 13
**Languages:** Common plus one other language
**Saving Throws:** Str +7, Con +7, Wis +6, Cha +7
**Damage Resistances:** necrotic; psychic
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned; stunned

---

### Traits

**Regeneration.** The revenant regains 10 Hit Points at the start of each of its turns. If the revenant takes Fire or Radiant damage, this trait doesn't function at the start of its next turn. Its body is destroyed only if it starts its turn with 0 Hit Points and doesn't regenerate.

**Undead Restoration.** If the revenant dies, it revives 24 hours later in a different body unless Dispel Evil and Good is cast on its corpse. If it revives, it animates a Humanoid corpse elsewhere on the same plane of existence; it now looks different but uses the same stat block and returns with all its Hit Points.


---

### Actions

**Multiattack.** The revenant uses Vengeful Glare and makes two Slam attacks.

**Slam.** m +7, reach 5 ft. *Hit:* 11 (2d6 + 4) Necrotic damage.

**Vengeful Glare.** wis DC 15, one creature the revenant can see within 30 feet.  The target has the Frightened condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically. If the Frightened target is cursed by the revenant (see Vow of Revenge), the target also has the Paralyzed condition for the duration.


---

### Bonus Actions

**Vow of Revenge (1/Day).** The revenant curses one creature it can see within 30 feet of itself. The revenant knows the distance to and direction of the cursed target, even if it is on a different plane of existence. The curse ends on the target if the revenant uses this Bonus Action on a different creature.


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
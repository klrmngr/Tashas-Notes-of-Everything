---
type: pc
race: "Humanoid"
class:
 - "Expert"
subClass:
 - "CR —"
cover: "Expert.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/—
  - source/slw
---
###### Expert
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: SLW
___

> [!infobox|no-t right]
> ![[Expert.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 15 (studded leather) |
> | :FasHeart: HP | 44 (8d8 + 8) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | SLW |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 12 | 14 | 10 | 14 |
| **Mod** | +0 | +3 | +1 | +2 | +0 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common, plus one of your choice
**Saving Throws:** Dex +6
**Skills:** Acrobatics +9, Performance +5, Persuasion +5, Sleight Of Hand +6, Stealth +9

---

### Traits

**Helpful.** The expert can take the Help action as a bonus action, and the creature who receives the help gains a 1d6 bonus to the d20 roll. If that roll is an attack roll, the creature can forgo adding the bonus to it, and then if the attack hits, the creature can add the bonus to the attack's damage roll against one target.

**Tools.** The expert has thieves' tools and a musical instrument.


---

### Actions

**Extra Attack.** The expert can attack twice, instead of once, whenever it takes the Attack action on its turn.

**Shortsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.

**Dagger.** Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage.

**Shortbow.** Ranged Weapon Attack: +6 to hit, range 80/320 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.


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
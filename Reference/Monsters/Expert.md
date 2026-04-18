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
  - source/dc
---
###### Expert
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: DC
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
> | :FasShield: AC | 17 (studded leather) |
> | :FasHeart: HP | 66 (12d8 + 12) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | DC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 20 | 12 | 14 | 10 | 14 |
| **Mod** | +0 | +5 | +1 | +2 | +0 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common, plus one of your choice
**Saving Throws:** Dex +9
**Skills:** Acrobatics +13, Performance +6, Persuasion +6, Sleight Of Hand +9, Stealth +13

---

### Traits

**Helpful.** The expert can take the Help action as a bonus action, and the creature who receives the help gains a 1d6 bonus to the d20 roll. If that roll is an attack roll, the creature can forgo adding the bonus to it, and then if the attack hits, the creature can add the bonus to the attack's damage roll against one target.

**Evasion.** When the expert is not incapacitated and subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, it instead takes no damage if it succeeds on the saving throw, and only half damage if it failed.

**Reliable Talent.** Whenever the expert makes an ability check that includes its whole proficiency bonus, it can treat a d20 roll of 9 or lower as a 10.

**Tools.** The expert has thieves' tools and a musical instrument.


---

### Actions

**Extra Attack.** The expert can attack twice, instead of once, whenever it takes the attack action on its turn.

**Shortsword.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 8 (1d6 + 5) piercing damage.

**Dagger.** Melee or Ranged Weapon Attack: +9 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 7 (1d4 + 5) piercing damage.

**Shortbow.** Ranged Weapon Attack: +9 to hit, range 80/320 ft., one target. *Hit:* 8 (1d6 + 5) piercing damage.


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
---
type: pc
race: "Humanoid"
class:
 - "Ambitious Assassin"
subClass:
 - "CR 5"
cover: "Ambitious Assassin.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/5
  - source/bmt
---
###### Ambitious Assassin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Ambitious Assassin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 (studded leather) |
> | :FasHeart: HP | 91 (14d8 + 28) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 18 | 15 | 18 | 14 | 16 |
| **Mod** | +0 | +4 | +2 | +4 | +2 | +3 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 10 ft., passive Perception 15
**Languages:** Common, thieves' cant, plus any one language
**Saving Throws:** Dex +7, Int +7
**Skills:** Deception +9, Perception +5, Stealth +10
**Condition Immunities:** charmed; frightened

---

### Traits

**Legendary Resistance (2/Day).** If the assassin fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The assassin makes two Poison Blade attacks.

**Poison Blade.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 6 (1d4 + 4) piercing damage plus 5 (1d10) poison damage.


---

### Reactions

**Uncanny Dodge.** When an attacker the assassin can see hits the assassin with an attack, the assassin halves the attack's damage against it.


---

### Legendary Actions

### 

**Cunning.** The assassin escapes nonmagical restraints and ends the grappled condition on itself, then moves up to its speed without provoking opportunity attacks.

**Stab (Costs 2 Actions).** The assassin makes one Poison Blade attack.

**Vanishing Escape (Costs 3 Actions).** The assassin creates a sudden distraction, such as a cloud of disorienting smoke or flash of dazzling light, filling a 10-foot cube within 5 feet of the assassin. Each creature of the assassin's choice in that area takes 9 (2d8) psychic damage, and the assassin has the invisible condition. This invisibility lasts until the end of the assassin's next turn.


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
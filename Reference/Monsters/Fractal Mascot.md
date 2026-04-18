---
type: pc
race: "Construct"
class:
 - "Fractal Mascot"
subClass:
 - "CR 1/4"
cover: "Fractal Mascot.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/small
  - cr/1-4
  - source/scc
---
###### Fractal Mascot
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Fractal Mascot.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Construct |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 27 (6d6 + 6) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 14 | 13 | 7 | 10 | 5 |
| **Mod** | +1 | +2 | +1 | -2 | +0 | -3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** understands the languages of its creator but can't speak
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Relative Density.** The fractal can move through creatures and objects as if they were 3. It takes 5 (1d10) force damage if it ends its turn inside an object.


---

### Actions

**Quantum Strike.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d4 + 1) force damage, or 6 (2d4 + 1) force damage if the fractal is Medium or bigger.


---

### Bonus Actions

**Augment.** The fractal's size increases by one category. While the fractal is Medium or bigger, it makes Strength checks and Strength saving throws with advantage. The fractal can become no larger than Huge via this bonus action.

**Diminish.** The fractal's size decreases by one category. While the fractal is Tiny, it makes attack rolls, Dexterity checks, and Dexterity saving throws with advantage. The fractal can become no smaller than 1 foot in height via this bonus action.


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
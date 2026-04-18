---
type: pc
race: "Fiend"
class:
 - "Space Clown"
subClass:
 - "CR 2"
cover: "Space Clown.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/2
  - source/bam
---
###### Space Clown
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Space Clown.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 58 (9d8 + 18) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 16 | 14 | 11 | 11 | 16 |
| **Mod** | +3 | +3 | +2 | +0 | +0 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Abyssal, Common
**Skills:** Acrobatics +5, Performance +5, Sleight Of Hand +5

---

### Traits

**Dying Burst.** When the clown drops to 0 hit points, it pops like a balloon, releasing a splash of putrid, corrosive ichor. Each creature within 5 feet of the clown when it bursts must make a DC 12 Dexterity saving throw, taking 10 (3d6) acid damage on a failed save, or half as much damage on a successful one.

**Squeakers.** The clown wears shoes that squeak when it walks. The squeaking can be heard out to a range of 30 feet. The squeaking is silenced while the clown's Phantasmal Form is in effect.


---

### Actions

**Shock.** Melee Spell Attack: +5 to hit, reach 5 ft., one target. *Hit:* 17 (4d6 + 3) lightning damage.

**Ray Gun.** Ranged Spell Attack: +5 to hit, range 120 ft., one creature. *Hit:* 7 (2d6) psychic damage, and if the target is a Humanoid with an Intelligence score of 3 or higher, it must make a DC 12 Wisdom saving throw. On a failed save, the target perceives everything it sees or hears as hilariously funny and is incapacitated for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


---

### Bonus Actions

**Phantasmal Form (3/Day).** The clown veils itself and everything it is wearing and carrying in an illusion that makes it look like some other creature of its size or smaller (such as a child) or an object small enough to fit in the clown's space (such as a floating balloon). Maintaining this effect requires the clown's concentration (as if concentrating on a spell), and the illusion fails to hold up to physical inspection. As an action, a creature that can see the clown's illusory form can make a DC 15 Wisdom (Insight) check, piercing the illusion and discerning the clown's true form on a success.


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
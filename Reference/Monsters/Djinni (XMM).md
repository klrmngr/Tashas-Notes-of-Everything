---
type: pc
race: "Elemental (genie)"
class:
 - "Djinni"
subClass:
 - "CR 11"
cover: "Djinni.png"
campaign:
locations:
tags:
  - race/genie
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/11
  - source/xmm
---
###### Djinni
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Djinni.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Large Elemental (genie) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 218 (19d10 + 114) |
> | :FasUserGroup: Race | Elemental (genie) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 15 | 22 | 15 | 16 | 20 |
| **Mod** | +5 | +2 | +6 | +2 | +3 | +5 |

**Speed:** 30 ft., fly 90 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 13
**Languages:** Primordial (Auran)
**Saving Throws:** Dex +6, Wis +7
**Damage Immunities:** lightning; thunder

---

### Traits

**Elemental Restoration.** If the djinni dies outside the Elemental Plane of Air, its body dissolves into mist, and it gains a new body in 1d4 days, reviving with all its Hit Points somewhere on the Plane of Air.

**Magic Resistance.** The djinni has Advantage on saving throws against spells and other magical effects.

**Wishes.** The djinni has a 30 percent chance of knowing the Wish spell. If the djinni knows it, the djinni can cast it only on behalf of a non-genie creature who communicates a wish in a way the djinni can understand. If the djinni casts the spell for the creature, the djinni suffers none of the spell's stress. Once the djinni has cast it three times, the djinni can't do so again for 365 days.


---

### Actions

**Multiattack.** The djinni makes three attacks, using Storm Blade or Storm Bolt in any combination.

**Storm Blade.** m +9, reach 5 feet. *Hit:* 12 (2d6 + 5) Slashing damage plus 7 (2d6) Lightning damage.

**Storm Bolt.** r +9, range 120 feet. *Hit:* 13 (3d8) Thunder damage. If the target is a Large or smaller creature, it has the Prone condition.

**Create Whirlwind.** The djinni conjures a whirlwind at a point it can see within 120 feet. The whirlwind fills a 20-foot-radius, 60-foot-high Cylinder centered on that point. The whirlwind lasts until the djinni's Concentration on it ends. The djinni can move the whirlwind up to 20 feet at the start of each of its turns.
Whenever the whirlwind enters a creature's space or a creature enters the whirlwind, that creature is subjected to the following effect. str DC 17 (a creature makes this save only once per turn, and the djinni is unaffected).  While in the whirlwind, the target has the Restrained condition and moves with the whirlwind. At the start of each of its turns, the Restrained target takes 21 (6d6) Thunder damage. At the end of each of its turns, the target repeats the save, ending the effect on itself on a success.


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
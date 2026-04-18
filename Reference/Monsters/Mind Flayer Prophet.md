---
type: pc
race: "Aberration"
class:
 - "Mind Flayer Prophet"
subClass:
 - "CR 8"
cover: "Mind Flayer Prophet.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/8
  - source/pabtso
---
###### Mind Flayer Prophet
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Phandelver and Below: The Shattered Obelisk
___

> [!infobox|no-t right]
> ![[Mind Flayer Prophet.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 97 (15d8 + 30) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Phandelver and Below: The Shattered Obelisk |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 14 | 14 | 20 | 17 | 17 |
| **Mod** | +2 | +2 | +2 | +5 | +3 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** Deep Speech, telepathy 120 ft., Undercommon
**Saving Throws:** Int +8, Wis +6, Cha +6
**Skills:** Arcana +8, Insight +6, Perception +6, Stealth +5

---

### Traits

**Awareness.** The mind flayer has advantage on initiative rolls and can't be surprised as long as it doesn't have the incapacitated condition.

**Magic Resistance.** The mind flayer has advantage on saving throws against spells and other magical effects.


---

### Actions

**Tentacles.** Melee Weapon Attack: +8 to hit, reach 5 ft., one creature. *Hit:* 16 (2d10 + 5) psychic damage. If the target is Medium or smaller, it has the grappled condition (escape DC 16) and must succeed on a DC 16 Intelligence saving throw or have the stunned condition until the grapple ends.

**Extract Brain.** Melee Weapon Attack: +8 to hit, reach 5 ft., one Humanoid grappled by the mind flayer. *Hit:* 55 (10d10) piercing damage. If this damage reduces the target to 0 hit points, the mind flayer kills it by extracting and devouring its brain.

**Mind Whip (Recharge 5–6).** The mind flayer lashes out with psychic energy, targeting up to two creatures it can see within 60 feet of itself. Each target must succeed on a DC 16 Intelligence saving throw or take 23 (4d8 + 5) psychic damage and have the stunned condition for 1 minute. A stunned target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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
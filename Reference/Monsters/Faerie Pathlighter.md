---
type: pc
race: "Fey"
class:
 - "Faerie Pathlighter"
subClass:
 - "CR 2"
cover: "Faerie Pathlighter.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/2
  - source/mcv4ec
---
###### Faerie Pathlighter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV4EC
___

> [!infobox|no-t right]
> ![[Faerie Pathlighter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 38 (7d8 + 7) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | MCV4EC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 12 | 13 | 17 | 18 |
| **Mod** | +0 | +2 | +1 | +1 | +3 | +4 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common, Sylvan
**Skills:** Insight +5, Perception +5, Survival +5

---

### Traits

**Faerie Illumination.** The faerie sheds dim light in a 15-foot radius.


---

### Actions

**Multiattack.** The faerie makes two Shining Strike attacks.

**Shining Strike.** Melee or Ranged Spell Attack: +6 to hit, reach 5 ft. or range 30 ft., one target. *Hit:* 7 (2d6) radiant damage, and if the target is a creature, it must succeed on a DC 14 Dexterity saving throw or be wreathed in light until the end of the faerie's next turn. While a creature is wreathed in light, attack rolls against the creature have advantage, and the creature can't benefit from the invisible condition.


---

### Bonus Actions

**Guiding Light (2/Day).** The faerie summons a 30-foot-radius sphere of magical light centered on itself, which lasts for 1 minute or until the faerie has the incapacitated condition. Each creature of the faerie's choice (other than the faerie) that starts its turn in that area gains 5 temporary hit points and has advantage on Wisdom saving throws and Wisdom checks until the start of its next turn.
The sphere is bright light, sheds dim light for an additional 30 feet, and moves with the faerie. If any of the sphere's area overlaps with an area of darkness created by a spell of 3rd level or lower, the spell that created the darkness is dispelled.


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
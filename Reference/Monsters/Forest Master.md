---
type: pc
race: "Celestial (unicorn)"
class:
 - "Forest Master"
subClass:
 - "CR 8"
cover: "Forest Master.png"
campaign:
locations:
tags:
  - race/unicorn
  - affinity/hostile
  - type/celestial
  - size/large
  - cr/8
  - source/mcv2dc
---
###### Forest Master
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV2DC
___

> [!infobox|no-t right]
> ![[Forest Master.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Celestial (unicorn) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 105 (14d10 + 28) |
> | :FasUserGroup: Race | Celestial (unicorn) |
> | :FasBook: Source | MCV2DC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 15 | 13 | 19 | 17 |
| **Mod** | +4 | +2 | +2 | +1 | +4 | +3 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 17
**Languages:** Celestial, Elvish, Sylvan, telepathy 60 ft.
**Saving Throws:** Int +4, Wis +7
**Skills:** Insight +7, Nature +4, Perception +7
**Damage Immunities:** poison
**Condition Immunities:** charmed; paralyzed; poisoned

---

### Traits

**Legendary Resistance (2/Day).** If the Forest Master fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** The Forest Master has advantage on saving throws against spells and other magical effects.

**Master of Beasts.** The Forest Master can comprehend and communicate with any Beast, even if the Beast knows no languages.


---

### Actions

**Multiattack.** The Forest Master makes either two Hooves attacks, two Moon Bolt attacks, or one of each.

**Hooves.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) bludgeoning damage.

**Moon Bolt.** Ranged Spell Attack: +7 to hit, range 60 ft., one target. *Hit:* 11 (2d6 + 4) radiant damage.


---

### Bonus Actions

**Erupting Briars (Recharge 4–6).** The Forest Master touches his horn to the earth and causes a 5-foot-tall wall of briars to erupt in a 90-foot line that is 10 feet wide. When the wall appears, each creature in its area is pushed into the nearest unoccupied space adjacent to the wall and must make a DC 15 Dexterity saving throw, taking 27 (6d8) piercing damage on a failed save or half as much damage on a successful one.
The wall of briars lasts until the start of the Forest Master's next turn. The wall blocks line of sight and counts as difficult terrain for all creatures except the Forest Master. The first time a creature enters the wall's area on a turn, that creature must succeed on a DC 15 Dexterity saving throw or take 13 (3d8) piercing damage.


---

### Reactions

**Misty Escape.** If the Forest Master takes damage from a melee attack, he, along with any equipment he is wearing or carrying, teleports to an unoccupied space within 30 feet that he can see.


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
---
type: pc
race: "Fey"
class:
 - "Leprechaun"
subClass:
 - "CR 4"
cover: "Leprechaun.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/small
  - cr/4
  - source/qftis
---
###### Leprechaun
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: QftIS
___

> [!infobox|no-t right]
> ![[Leprechaun.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Small Fey |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 52 (8d6 + 24) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | QftIS |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 17 | 16 | 12 | 14 | 18 |
| **Mod** | -2 | +3 | +3 | +1 | +2 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Common, Sylvan
**Saving Throws:** Con +5, Wis +4
**Skills:** Perception +4, Sleight Of Hand +7, Stealth +5

---

### Traits

**Industrious.** The leprechaun is proficient with all artisan's tools and adds double its proficiency bonus to ability checks made with them.

**Reluctant Refusal.** When a creature offers the leprechaun the chance to partake in merriment or revelry such as a song, a dance, or a good meal, the leprechaun must succeed on a DC 15 Wisdom saving throw or have the charmed condition for 24 hours. While charmed in this way, the leprechaun partakes of the offering, treats the creature as a trusted friend, and seeks to defend it from harm. The charmed condition ends if the creature or any of its allies damage the leprechaun, force the leprechaun to make a saving throw, or steal from the leprechaun.


---

### Actions

**Multiattack.** The leprechaun makes two Cobbler's Hammer attacks and can use Spellcasting.

**Cobbler's Hammer.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) bludgeoning damage plus 13 (3d8) force damage. If the target is a creature, its speed is halved until the start of the leprechaun's next turn.

**Gift of Luck (1/Day).** The leprechaun touches a creature and magically gifts the target a measure of luck. The creature gains the leprechaun's Astonishing Luck reaction. The creature can use the reaction three times, after which this gift goes away. The leprechaun can revoke this gift from a creature at any time (no action required). A creature can benefit from only one leprechaun's Gift of Luck at a time.


---

### Bonus Actions

**Cunning Trick.** The leprechaun takes the Disengage or Hide action or makes a Dexterity (Sleight of Hand) check.


---

### Reactions

**Astonishing Luck.** When the leprechaun fails an ability check, an attack roll, or a saving throw, it can roll a new d20 and choose which roll to use, potentially turning the failure into a success.


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
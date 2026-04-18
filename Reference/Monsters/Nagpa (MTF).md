---
type: pc
race: "Humanoid (nagpa)"
class:
 - "Nagpa"
subClass:
 - "CR 17"
cover: "Nagpa.png"
campaign:
locations:
tags:
  - race/nagpa
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/17
  - source/mtf
---
###### Nagpa
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Nagpa.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (nagpa) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 187 (34d8 + 34) |
> | :FasUserGroup: Race | Humanoid (nagpa) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 15 | 12 | 23 | 18 | 21 |
| **Mod** | -1 | +2 | +1 | +6 | +4 | +5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 20
**Languages:** Common plus up to five other languages
**Saving Throws:** Int +12, Wis +10, Cha +11
**Skills:** Arcana +12, Deception +11, History +12, Insight +10, Perception +10

---

### Traits

**Corruption.** As a bonus action, the nagpa targets one creature it can see within 90 feet of it. The target must make a DC 20 Charisma saving throw. An evil creature makes the save with disadvantage. On a failed save, the target is charmed by the nagpa until the start of the nagpa's next turn. On a successful save, the target becomes immune to the nagpa's Corruption for the next 24 hours.

**Paralysis (Recharge 6).** As a bonus action, the nagpa forces each creature within 30 feet of it to succeed on a DC 20 Wisdom saving throw or be paralyzed for 1 minute. A paralyzed target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. Undead and constructs are immune to this effect.


---

### Actions

**Staff.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 9 (2d6 + 2) bludgeoning damage.


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
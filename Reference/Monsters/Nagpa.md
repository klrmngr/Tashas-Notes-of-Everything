---
type: pc
race: "Monstrosity (wizard)"
class:
 - "Nagpa"
subClass:
 - "CR 17"
cover: "Nagpa.png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/17
  - source/mpmm
---
###### Nagpa
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Nagpa.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Medium Monstrosity (wizard) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 203 (37d8 + 37) |
> | :FasUserGroup: Race | Monstrosity (wizard) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

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

### Actions

**Multiattack.** The nagpa makes three Staff or Deathly Ray attacks. It can replace one attack with a use of Spellcasting.

**Staff.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 9 (2d6 + 2) bludgeoning damage plus 24 (7d6) necrotic damage.

**Deathly Ray.** Ranged Spell Attack: +12 to hit, range 120 ft., one target. *Hit:* 30 (7d6 + 6) necrotic damage.


---

### Bonus Actions

**Corruption.** The nagpa targets one creature it can see within 90 feet of it. The target must make a DC 20 Charisma saving throw. An evil creature makes the save with disadvantage. On a failed save, the target is charmed by the nagpa until the start of the nagpa's next turn. On a successful save, the target becomes immune to the nagpa's Corruption for the next 24 hours.

**Paralysis (Recharge 6).** The nagpa forces each creature within 30 feet of it to make a DC 20 Wisdom saving throw, excluding Undead and Constructs. On a failed save, a target is paralyzed for 1 minute. A paralyzed target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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